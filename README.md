# 🛡️ Secure Healthcare Information Network System

A Cisco Packet Tracer project simulating a secure, scalable, and redundant enterprise network for a modern healthcare environment.  
Designed with 75+ nodes across multi-floor departments, cloud services, and data center integration.

---

## 📖 Project Overview

This project models a real-world hospital network with emphasis on **security**, **high availability**, and **efficient segmentation**.  
It includes:

- Pharmacy and Medical Labs
- Reception and Guest Areas
- Doctors' Consultancy Departments
- Procurement and Financial Management
- Corporate Auditors Section
- IT Team Operations
- Cloud Integration (AWS EC2, RDS) and Private Data Centers (DMZ)

---

## 🏗️ Key Features

- 75+ Network Nodes (Routers, Switches, PCs, Servers, Wireless Controllers)
- VLAN Segmentation for Departmental Isolation
- High Availability using HSRP (Hot Standby Router Protocol)
- LACP (Link Aggregation Control Protocol) for link redundancy
- DMZ Implementation with Servers and Firewalls
- Cloud Service Simulation for Hospital Data
- Centralized Wireless Management using WLC (Wireless LAN Controller)

---

## 🌐 Addressing Scheme

| Department/Zone | Subnet |
|-----------------|--------|
| VLAN Network    | `10.0.0.0/16` |
| LAN Devices     | `192.168.0.0/20` |
| VRRP Addresses  | `172.66.0.0/20` |
| DMZ Servers     | `10.20.10.0/26` |

---

## 🚀 How to Run the Project

1. Open the `.pkt` file using **Cisco Packet Tracer**.
2. Review the network topology, device configuration, and VLAN setup.
3. Run network simulations: Ping tests, Traceroutes, Redundancy Failover.
4. Customize IP addresses, VLAN IDs, or add additional nodes if required.

---
