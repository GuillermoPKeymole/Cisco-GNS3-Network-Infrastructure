# Cisco GNS3 Network Infrastructure – Enterprise Project

This repository showcases a complete enterprise network design and implementation project.It includes **Cisco IOS**, **GNS3**, and open-source systems such as **AlmaLinux** and **Ubuntu**.

## 🌐 Project Overview

This GNS3-based project simulates a real-world enterprise network connecting **Montreal** and **Toronto** sites. It demonstrates complete routing, VLAN segmentation, VPN, VoIP, NAT, DHCP, and DNS services across multiple devices and technologies.

### 🧠 Core Features:
- VLAN segmentation (IT, HR, Sales, VoIP)
- Inter-VLAN routing using Layer 3 switches
- IPsec VPN between Montreal and Toronto
- NAT and secure SSH remote access
- DHCP, DNS, HTTP, SSH services on Linux VMs
- Cisco CME voice network with IP Phones
- ACL-based access control
- Full network and service validation using CLI tests

---

## 🖼️ Network Topology

![Network Topology](Network%20Visual%20Topology.png)

---

## 🧰 Included Files

### 🔧 Configuration and Project Files
- `project.gns3` – The main GNS3 project file.
- `Project 1 - Guillermo PK - Configurations.pdf` – All interface and routing configurations.

### 📄 Documentation
- `Network Design and Implementation Project.pdf` – Detailed project goals, IP schemes, and subnetting plan.
- `Network Design and Implementation Tests.pdf` – All test cases and results used to validate connectivity and services.

## 💾 Base Images and VMs (For Educational Use Only)

These files are required to run the GNS3 project. Due to size limitations, they are not included directly in the GitHub repository. Store them externally or compress and link them via your portfolio.

| Filename | Description |
|----------|-------------|
| `vios-adventerprisek9-m.vmdk.SPA.157-3.M3` | Cisco IOSv image for routers |
| `vios_l2-adventerprisek9-m.ssa.high_iron_20190423.qcow2` | Cisco IOSv-L2 image for switches |
| `c7200-adventerprisek9-mz.124-24.T5.image` | Cisco 7200 series image (for CME) |
| `c7200-adventerprisek9-mz.124-24.T5.image.md5sum` | MD5 checksum file for integrity validation |
| `Linux.GUI.qcow2` | Ubuntu desktop-based GUI client |
| `IOSv_startup_config.img` | Startup configuration for Cisco IOSv devices |
| `AlmaLinux-9-GenericCloud-9.2-20230513.x86_64.qcow2` | AlmaLinux cloud-ready image for server roles |
| `almalinux-cloud-init-data.iso` | Cloud-init ISO used to preconfigure AlmaLinux VMs |

You must manually add and associate these images within GNS3 before running the project.

---

## 🖥 Technologies Used

- **GNS3** (v2.2+) Network Emulator
- **Cisco IOSv Routers and IOSv-L2 Switches**
- **Cisco C7200 Router**
- **Cisco IP Phones (VLAN 40) + CME**
- **AlmaLinux** for web and SSH services
- **Ubuntu Clients** for user testing and validation
- **Apache2**, DHCP, DNS, SSH

---

## 🧪 Key Services Configured

| Service | Technology |
|--------|------------|
| DHCP | Cisco IOS Router |
| DNS | Ubuntu with BIND9 |
| Web Server | Apache2 |
| NTP | Chrony (AlmaLinux) |
| VoIP | Cisco CME |
| NAT & VPN | Cisco Routers |
| SSH Access | Linux Servers |
| VLAN/ACLs | Cisco Switches |

---

## 🚀 How to Use

To use the `project.gns3` file:

1. Install **GNS3 (v2.2+)**
2. Ensure you have the required Cisco IOS images and linked QEMU VMs:
   - `IOSv` for routers (15.2)
   - `IOSv-L2` for switches
   - QEMU VMs for **AlmaLinux** and **Ubuntu**
3. Open GNS3 and import `project.gns3` manually
4. Connect your images using the same **compute IDs** (already stripped from snapshots and base images)

---

## 🧑‍💻 Author

**Guillermo Padilla Keymole**  
Student, Network Administration AEC  
John Abbott College  
[Portfolio Website](https://guillermopkeymole.github.io/GPKTechPortfolio/)  

---

## 📜 License

**For educational use only.**  
Cisco IOS and QEMU image files are included solely for learning purposes and should not be redistributed.

---
