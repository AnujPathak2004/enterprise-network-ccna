# enterprise-network-ccna
CCNA enterprise network project with OSPF, VLAN, NAT and ACL
# 🌐 Enterprise Network Design (CCNA Project)

## 📌 Overview

This project demonstrates a multi-site enterprise network built using Cisco Packet Tracer. It includes VLAN segmentation, dynamic routing, NAT for internet access, and security using ACLs.

---

## 🏗️ Network Architecture

* Head Office (HQ) with 3 departments:

  * HR (VLAN 10)
  * IT (VLAN 20)
  * Sales (VLAN 30)
* Branch 1 and Branch 2 networks
* ISP simulation for internet connectivity

---

## ⚙️ Technologies Used

* OSPF (Open Shortest Path First) – Dynamic routing
* VLAN & Inter-VLAN Routing
* NAT (PAT) – Internet access
* ACL (Access Control List) – Security
* HSRP – Gateway redundancy

---

## 🌐 IP Addressing Scheme

| Network         | Subnet          |
| --------------- | --------------- |
| VLAN 10 (HR)    | 192.168.10.0/24 |
| VLAN 20 (IT)    | 192.168.20.0/24 |
| VLAN 30 (Sales) | 192.168.30.0/24 |
| Branch 1        | 192.168.40.0/24 |
| Branch 2        | 192.168.50.0/24 |

---

## 🔐 Security Implementation

* Configured ACL to block HR network from accessing IT network
* Allowed all other traffic for normal operations

---

## 🌍 Features

* Full connectivity between HQ and branches
* Internet access using NAT (PAT)
* Dynamic routing using OSPF
* Network segmentation using VLANs

---

## 🧪 Testing & Verification

### ✅ Connectivity Test

* Successfully pinged across VLANs and branch networks
* Verified internet access using NAT

### 🔁 OSPF Verification

* Routes learned dynamically across all routers

### 🌐 NAT Verification

* Private IPs translated to public IP using PAT

### 🔒 ACL Verification

* HR network blocked from accessing IT network

---

## 📸 Screenshots

### 🗺️ Topology

<img width="1917" height="1021" alt="topology" src="https://github.com/user-attachments/assets/dc771867-c83f-42c0-81ca-12ef4d3e01ba" />


### 🌐 Ping Test

<img width="1919" height="1018" alt="branch pc" src="https://github.com/user-attachments/assets/0ccaaaf0-96b9-411b-a659-a7fecab664cc" />
<img width="1912" height="1017" alt="ho pc" src="https://github.com/user-attachments/assets/6b1a56df-4476-4daa-8756-5cfd32b2452f" />



### 🔁 OSPF Routes

<img width="1863" height="625" alt="ospf working" src="https://github.com/user-attachments/assets/efd51f4b-d71c-4b3f-85d9-ab4a9e376592" />


### 🌍 NAT Translation

<img width="1870" height="242" alt="nat translations" src="https://github.com/user-attachments/assets/bdb3befe-d958-41f5-a3bb-bfa6753486cf" />


### 🔒 ACL Test
<img width="1853" height="708" alt="ACL working" src="https://github.com/user-attachments/assets/a7425be9-38df-4009-8483-e026136b8e53" />



---

## 🚀 Outcome

Successfully designed and implemented a scalable enterprise network with routing, security, and internet connectivity.

---

## 👨‍💻 Author

Anuj Pathak
