# Cisco GNS3 Network Infrastructure – Enterprise Project

This repository contains a complete enterprise network design and implementation project developed using **Cisco IOS**, **GNS3**, and open-source systems such as **AlmaLinux** and **Ubuntu**.

## 📁 Project Files Included

| File | Description |
|------|-------------|
| `Network Design and Implementation Project.pdf` | Full project report including requirements, design decisions, and implementation plan |
| `Network Design and Implementation Tests.pdf` | Functional tests for validating DHCP, DNS, FTP, NTP, Apache, and access restrictions |
| `Project 1 - Guillermo PK - Configurations.pdf` | Raw Cisco IOS configurations, Linux service configurations, and CLI outputs |
| `Network Visual Topology.png` | High-resolution topology map of the enterprise network |
| `project.gns3` | GNS3 project file (requires external IOS/QEMU images on your local setup) |

---

## 🧠 Project Overview

This project simulates a real-world network connecting **Montreal** and **Toronto** sites with:
- VLAN segmentation (IT, HR, Sales, VoIP)
- DHCP, DNS, FTP, Apache, NTP services
- Cisco Voice (CME)
- Firewall and NAT configuration
- Subnetting and Inter-VLAN Routing
- Access Control (ACLs, user restrictions, file types)
- Static and dynamic routing (RIPv2 and static)
- Authentication and Authorization via Apache and Linux file permissions

---

## 🖥 Technologies Used

- **Cisco IOSv Routers and Switches (GNS3)**
- **AlmaLinux** (Web, FTP, DNS, NTP servers)
- **Ubuntu Clients** (PC1, PC2, etc.)
- **Apache2** with subnet and user-based access controls
- **FileZilla, Evolution Mail, and CLI tools** for validation
- **Cisco IP Phones** for VoIP (VLAN40)

---

## 🧪 Key Services Configured

| Service | Technology |
|--------|------------|
| DHCP | ISC DHCP Server & Cisco Router |
| DNS | BIND9 |
| FTP | VSFTPD |
| Web Server | Apache2 |
| NTP | Chronyd |
| VoIP | Cisco CME |
| Authentication | Apache Basic Auth + `.htaccess` |
| Subnet Access | Apache `Require ip` + ACLs |

---

## 🔧 Requirements to Run the GNS3 Project

To use the `.gns3project` file:

1. Install **GNS3 (v2.2+)**
2. Ensure you have the required Cisco IOS images and linked QEMU VMs:
   - `IOSv` for routers (15.2)
   - `IOSv-L2` for switches
   - QEMU VMs for **AlmaLinux** and **Ubuntu**
3. Open GNS3 and import `project.gns3` manually
4. Connect your images using the same **compute IDs** (already stripped from snapshots and base images)

---

## 🏁 Status

✅ Completed  
📄 Documented  
💡 Portfolio-Ready

---

## 🧑‍💻 Author

**Guillermo Padilla Keymole**  
Student, Network Administration AEC  
John Abbott College  
[Portfolio Website](https://guillermopkeymole.github.io/GPKTechPortfolio/)  

---

## 📸 Preview

![Network Topology](Network%20Visual%20Topology.png)
