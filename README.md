# Enterprise Networking Lab (Packet Tracer)

This project is a **Cisco Packet Tracer (`.pka`) lab** based on Jeremy’s IT Lab enterprise design.  
It simulates a small enterprise network with **two offices** connected through a redundant core.  
I’m using this project to apply the concepts I learn during my CCNA preparation.

---

## 🗂️ Project Structure
- `Enterprise_Lab.pka` → Main Packet Tracer lab file
- `README.md` → Documentation (this file)

---

## 🏢 Topology Overview
The lab follows a **3-tier hierarchical network design**:
- **Core Layer**: 2 Core Switches (CSW1, CSW2) connected to the Router (R1) and Internet
- **Distribution Layer**: 2 Distribution Switches per office (DSW-A1/A2, DSW-B1/B2)
- **Access Layer**: Multiple Access Switches connecting PCs, Phones, Laptops, and Server
- **Wireless**: WLC + LWAPs in both offices
- **End Devices**: PCs, IP Phones (Voice VLANs), Laptops, Server (SRV1)

📸 *[Insert topology screenshot here]*

---

## 🎯 Learning Goals
Each version of this lab will implement new CCNA concepts step by step:

1. **Basic Setup**
   - Device addressing
   - VLAN creation
   - Switchport assignments  

2. **Redundancy & Reliability**
   - STP (Spanning Tree Protocol)  
   - EtherChannel (link aggregation)  

3. **Routing**
   - Inter-VLAN Routing  
   - Static routes / OSPF basics  

4. **Services**
   - DHCP configuration  
   - DNS/HTTP on SRV1  

5. **Wireless**
   - WLC and LWAP registration  
   - WLAN SSIDs and security  

---

## 🚀 How to Use
1. Download [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).  
2. Clone this repo:
   ```bash
   git clone (https://github.com/Athuldev1/ccna-enterprise-topology.git)
