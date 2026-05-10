# Enterprise SD-WAN & Network Security Lab

This repository contains a comprehensive technical project for deploying a professional multi-site enterprise network. The lab is built on **Fortinet (FortiGate)** and **Cisco** platforms, focusing on SD-WAN optimization, high availability, and multi-layer security.

## 🚀 Key Technical Features
- **Fortinet SD-WAN:** Advanced traffic steering and automatic failover between dual-ISP links (VNPT & FPT).
- **Security Posture:** Layer 4-7 firewall policies, Web Filtering, Application Control, and IPv4 DoS protection.
- **Site-to-Site Connectivity:** Secure IPsec VPN tunnels for permanent connection between Headquarter (HQ) and Branch Office (BR).
- **Remote Access:** **IPsec VPN (Remote Access)** implementation for secure and high-performance remote workforce connectivity.
- **Switching Infrastructure:** - Cisco EtherChannel (LACP) & VLAN segmentation.
- **Switching Infrastructure:** Cisco EtherChannel (LACP), VLAN segmentation, Port Security (MAC filtering), and STP hardening (BPDU/Root Guard).

## 📂 Repository Contents
- **`Enterprise-SDWAN-Lab-Guide-Vu-Quang-Khai.pdf`**: Full technical report, IP planning, and configuration steps.
- **`Lab_Completed.zip`**: Complete EVE-NG lab file with all settings applied. Ready for testing.
- **`Lab_Uncompleted.zip`**: Clean topology file with no configurations. Best for practice and follow-along.

## 🛠 Prerequisites
- **Emulator:** EVE-NG (Community or Professional).
- **Required Images:**
  - FortiGate v6.4.5.
  - Cisco IOL/vIOS (L2 and L3).
  - Windows/Linux nodes for end-point testing.

## 📖 How to Get Started
1. **Import Lab:** Open your EVE-NG dashboard and upload the `.unl` files.
2. **Setup Nodes:** Ensure you have the correct FortiGate and Cisco images named in the lab.
3. **Follow the Guide:** Use the provided PDF guide to understand the network logic or to configure the initial topology from scratch.

## 👤 Author
- **Vu Quang Khai**
- Project Date: May 2026
