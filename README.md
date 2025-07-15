# 🧠 Network Design and Implementation – GNS3 Project

This repository showcases a full network infrastructure project designed and tested using GNS3. It includes network topology, configuration files, base images used in the simulation, and full documentation of implementation and testing.

---

## 📁 Repository Overview

| Folder | Description |
|--------|-------------|
| `GNS3-Project/` | Contains the GNS3 project file (`project.gns3`) used to recreate the network. |
| `Documentation/` | Includes the planning document, test plan, and the final configuration guide. |
| `Topology/` | Network diagram showing the full logical topology for Montreal and Toronto sites. |
| `Images-and-VMs/` | Base Cisco images, QEMU VMs, and cloud-init ISO used in the lab environment. |

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

### 💾 Base Images and VMs (For Educational Use)
- `vios-adventerprisek9-m.vmdk.SPA.157-3.M3`
- `vios_l2-adventerprisek9-m.ssa.high_iron_20190423.qcow2`
- `c7200-adventerprisek9-mz.124-24.T5.image`
- `Linux.GUI.qcow2`, `IOSv_startup_config.img`
- `AlmaLinux-9-GenericCloud-9.2.qcow2` (used for server deployment)
- `almalinux-cloud-init-data.iso`

> ⚠️ **Note:** Due to file size and licensing, you may need to host the `/Images-and-VMs` folder separately or provide download instructions. These are not guaranteed to work out of the box without your local compute environment.

---

## ✅ Features Implemented

- Multi-site network (Montreal + Toronto)
- VLAN segmentation (IT, Sales, HR, VoIP)
- Inter-VLAN routing
- DMZ web server (AlmaLinux)
- CME VoIP routing
- NAT and internet edge simulation
- Connectivity tested using Ubuntu and IP phones

---

## 🚀 Getting Started

To run this lab:

1. Clone the repository.
2. Open GNS3 and import `project.gns3` from the `GNS3-Project` folder.
3. Make sure your GNS3 VM is configured with the same Cisco/QEMU images.
4. Refer to the `Configurations.pdf` file to verify and adjust any interface or routing setup.

---

## 📚 Author

**Guillermo Padilla Keymole**  
Student – Network Administration AEC  
John Abbott College  
GitHub Portfolio: [guillermopkeymole.github.io/GPKTechPortfolio](https://guillermopkeymole.github.io/GPKTechPortfolio)

---

## 📝 License

Educational use only. Cisco IOS images and QEMU VMs are included for demonstration purposes and should not be redistributed.
