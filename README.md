# Campus Network Design (Cisco Packet Tracer)

## Overview
This project demonstrates a **multi-campus network design** consisting of a Main Campus and a Branch Campus interconnected via a WAN link. The network is segmented using VLANs to ensure security, scalability, and efficient traffic management.

---

## Network Architecture

### Main Campus
Divided into three buildings:

- **Building A (Admin Departments)**
  - HR → VLAN 10 → 192.168.1.0/24  
  - Admin → VLAN 20 → 192.168.2.0/24  
  - Finance → VLAN 30 → 192.168.3.0/24  
  - Business → VLAN 40 → 192.168.4.0/24  

- **Building B (Academic Departments)**
  - Engineering → VLAN 50 → 192.168.5.0/24  
  - Art & Design → VLAN 60 → 192.168.6.0/24  

- **Building C (Services)**
  - Student Lab → VLAN 70 → 192.168.7.0/24  
  - IT Department → VLAN 80 → 192.168.8.0/24  

Includes:
- Web Server  
- FTP Server  

---

### Branch Campus
- Staff Floor → VLAN 90 → 192.168.9.0/24  
- Student Floor → VLAN 100 → 192.168.10.0/24  

---

## Connectivity
- WAN Link between campuses → `10.10.10.0/30`
- Cloud Network (Email Server) → `20.20.20.0/30`

---

## Key Features
- VLAN Segmentation  
- Inter-VLAN Routing  
- WAN Connectivity  
- Centralized Services  
- Scalable Design  

---

## Network Topology
(Add your diagram image here)

---

## Files Included
- `Campus-Network.pkt` (Packet Tracer file)
- Network Diagram
- Configuration files (if added)

---

## Learning Outcomes
- VLAN configuration and subnetting  
- Router and switch configuration  
- Enterprise network design concepts  
- Troubleshooting network connectivity  

---
