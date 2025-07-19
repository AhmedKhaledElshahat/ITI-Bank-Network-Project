# 🏦 ITI - Bank Network Project

This repository contains the complete configuration and documentation of a simulated network infrastructure for the new branch of Bank.

---

## 🖼️ Network Topology

![Project Topology]([ITI CCNA.png](https://github.com/AhmedKhaledElshahat/ITI-Bank-Network-Project/blob/master/ITI%20CCNA.png))

---

## 🔧 Project Objectives

- Design a scalable and secure network for a bank branch.
- Implement subnetting and VLAN segmentation.
- Configure inter-VLAN routing using Router-on-a-Stick.
- Enable OSPF for dynamic routing between routers.
- Secure access with SSHv2 and port security.
- Ensure end devices can communicate across VLANs and remote offices.

---

## 🖥️ Network Structure

- **Subnetting**: 172.16.10.0/24 divided into 8 subnets using /27 mask.
- **VLANs**:
  - VLAN 10 – Management (CEO)
  - VLAN 20 – Marketing (Copyrighters)
  - VLAN 30 – Accounting (Dialers)
  - VLAN 100 – Native VLAN for trunk links
- **Router-on-a-Stick**:
  - Sub-interfaces configured on R1 to route between VLANs.
- **Dynamic Routing**:
  - OSPF is configured between R1, R2, and R3.
- **Security**:
  - SSHv2 enabled on R3 and S1-Office3.
  - Port security enabled on all access ports.

---

## 📁 Files Included

- `Project Documentation.docx` – Full documentation of IP assignments and network design.
- `ITI-Bank Network Project.pkt` – Cisco Packet Tracer file containing the full lab setup and configuration (not included here – to be added).
- `FLSM Subnetting Table.docx` – Subnetting table using Fixed Length Subnet Masking (FLSM).
- `Project Topology.png` – Visual representation of the entire network topology.
- `README.md` – Project overview.

---

## ✅ Skills Demonstrated

- Network design and IP planning
- VLAN and inter-VLAN configuration
- Routing protocol implementation (OSPF)
- SSH configuration and switch security
- Realistic documentation and topology planning

---

## 📬 Contact

**Prepared by:** Ahmed khaled
**LinkedIn:** [www.linkedin.com/in/ahmed-khaled-37aa46236](https:www.linkedin.com/in/ahmed-khaled-37aa46236)

Feel free to clone or fork this repository to explore or reuse parts of the network setup.
