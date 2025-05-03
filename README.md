# 🏥 Hospital Network Design (Cisco Packet Tracer)

This project presents a detailed **Hospital Network Design** using **Cisco Packet Tracer**, built for a Health Care Management System. The topology is fully segmented and supports essential hospital services and departments.

---

## 📄 Abstract

The design simulates a hospital's local area network (LAN), connecting nodes such as PCs, routers, switches, and mobile devices. These nodes communicate via copper or fiber links. The network ensures efficient data flow and security using services like DHCP, DNS, SSH, and HTTPS. It is scalable and adaptable to real-world hospital environments.

---

## 🏥 Hospital Departments & Segments

1. **General Ward** (`192.168.4.0/24`)  
   - Reception: `192.168.4.2`  
   - Doctor (Dr Arslan): `192.168.4.3`

2. **Private Ward** (`192.168.5.0/24`)  
   - Reception: `192.168.5.2`  
   - Doctor (Dr Muneeb Awan): `192.168.5.3`

3. **Clinical Area** (`192.168.2.0/24`)  
   - Clinical Reception: `192.168.2.2`  
   - Test Room: `192.168.2.5`  
   - Ultrasound Room: `192.168.2.3`  
   - Operation Theater: `192.168.2.4`

4. **IT Department** (`192.168.1.0/24`)  
   - IT Reception: `192.168.1.6`  
   - Servers:
     - DNS + HTTP: `192.168.1.3`
     - SMTP + FTP: `192.168.1.4`

5. **Entrance Reception** (`192.168.3.0/24`)  
   - Information Counter: `192.168.3.3`  
   - Main Reception: `192.168.3.2`  
   - Billing Counter: `192.168.3.4`

6. **Lobby / Public Area**  
   - Wi-Fi Router (`WRT300N`)  
   - Connected Devices: Tablets and Smartphones (Guests 1–4)

---

## 🔧 Network Devices Used

- **Routers**: Cisco Router-PT (Core, IT, Clinical, Entrance, General Ward, Private Ward)
- **Switches**: 2960 & 2960-24TT
- **Wireless Router**: WRT300N for guest access
- **End Devices**: PCs, Smartphones, Tablets
- **Servers**: DNS, HTTP, FTP, SMTP

---

## 🔐 Features and Services

- **DHCP** – Dynamic Host Configuration
- **DNS** – Name Resolution
- **VLSM / Subnetting** – Efficient IP Management
- **HTTPS / HTTP** – Web Services
- **SSH** – Secure Remote Access
- **SMTP / FTP** – Email & File Transfer
- **WiFi** – Wireless Network for Guests

---

## 🌐 Topology Design Highlights

- **Full IP Addressing** with `192.168.x.0/24` subnets using VLSM.
- **Routers Interconnected via Serial Links** (`192.168.8.0/30` and `192.168.7.0/30`).
- **Switch-Based Segments** per Department.
- **Secure and Logical Design** for clear data flow and management.
- **Commented Diagram** (Refer to `Hospital_Network.pkt` file).

---

## 📁 Project Files

- `Hospital_Network.pkt` – Cisco Packet Tracer topology
- `README.md` – Project documentation

---

## 📸 Preview

![Network Topology](b2ce5bb6-16f6-40f2-a0bd-a5cd506335cd.png)

---

## 📌 Summary

This network design for a hospital demonstrates logical segmentation, secure communication, and practical implementation using Cisco Packet Tracer. It is ideal for healthcare facilities aiming to deploy structured IT infrastructure.

---

## 👤 Author

*kalpa dhananjaya*  
IT Student | Network Enthusiast
