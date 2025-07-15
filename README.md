# Cisco GNS3 Network Infrastructure Project – John Abbott College

This repository showcases a **fully simulated enterprise network infrastructure** designed and implemented using **GNS3** as part of the **Network Administration AEC** program at **John Abbott College**. The project includes both a **network design blueprint** and **live validation tests**, demonstrating hands-on skills in Cisco IOS, switching, routing, voice, VPNs, and Linux services.

---

## 🧠 Project Summary

This GNS3 project demonstrates a multi-site corporate network with VLAN segmentation, OSPF routing, NAT, IPSec VPN, CME VoIP, DHCP, and external NAT access. All configurations were done from scratch using Cisco IOS CLI and Linux server/client systems.

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| [`project.gns3`](./project.gns3) | GNS3 project file (without base images, for reference) |
| [`Network Design and Implementation Project.pdf`](./Network%20Design%20and%20Implementation%20Project.pdf) | Full network design, topology diagram, addressing plan |
| [`Project 1 - Guillermo PK - Configurations.pdf`](./Project%201%20-%20Guillermo%20PK%20-%20Configurations.pdf) | All device configurations (routers, switches, servers) |
| [`Network Design and Implementation Tests.pdf`](./Network%20Design%20and%20Implementation%20Tests.pdf) | Validation test plan and device-specific test commands |

---

## 🔧 Technologies and Skills

- **GNS3 Virtual Lab** with routers, switches, and Linux VMs
- **Cisco IOS configuration** (RIP/OSPF, NAT, DHCP, VLAN, trunking)
- **IPSec VPN tunnels**
- **Cisco CME** (VoIP) setup with IP Phones
- **AlmaLinux and Ubuntu** integration for server/client services
- **NAT and firewall rule validation** via HTTP and SSH tests
- **Troubleshooting with CLI tools** like `show ip route`, `show vlan`, `debug`, and `Wireshark`

---

## ✅ Sample Validations (from Tests)

- **IP reachability and NAT** between internal clients and external servers
- **OSPF neighbor relationships and routing tables**
- **DHCP lease bindings on R1 and R2**
- **VoIP registration on CME with working IP Phones**
- **IPSec VPN tunnel status and ESP packet verification**
- **SSH/telnet and HTTP service accessibility across VLANs and sites**

---

## 🔗 Live Preview and Screenshots

For visual reference and screenshots, view this project under the **Projects** section of my portfolio:  
📁 [https://guillermopkeymole.github.io/GPKTechPortfolio](https://guillermopkeymole.github.io/GPKTechPortfolio)

---

## 👨‍💻 Author

**Guillermo Padilla Keymole**  
AEC – Network Administration  
John Abbott College  
📍 Montreal, Canada

---

## 🌐 Connect

- [GitHub Portfolio](https://github.com/GuillermoPKeymole)
- [LinkedIn](https://www.linkedin.com/in/guillermo-padilla-keymole-a24328363)

---
