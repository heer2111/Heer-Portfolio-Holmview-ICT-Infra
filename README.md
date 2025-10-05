# Secure Network Design – Holmview Primary School (Capstone Project)

This repository presents the technical artefacts and configurations I created as part of my contribution to the "Holmview Primary School Secure Network" project. My role was "Wi-fi and IoT engineer", to design, configure, and document the **entire network topology, IP schema, VLAN setup, DHCP configuration, wireless network segmentation, and IoT integration** using Cisco Packet Tracer.

---

## My Technical Contributions

### 1.  Full Network Topology Design  
I built and logically arranged all networking devices, including core switches, access switches, routers, wireless access points, servers, PCs, printers, IoT cameras, and smart door devices.

**Screenshot:** ![Network Topology](01_NetworkTopologyOverview.png)


---

### 2. IP Addressing and Subnetting Table  
I planned and implemented the full IP addressing scheme using CIDR notation and subnetting best practices for 6 VLANs.

- Subnet sizes calculated based on host requirements  
- Default gateways assigned for each VLAN  
- CIDR notation used for efficiency  

**Screenshot:** `02_IPAddressingTable.png`

---

### 3. DHCP Pool Configuration  
I configured 6 separate DHCP pools in the router to dynamically assign IP addresses within their respective subnets. Each pool includes:

- Correct default gateway  
- DNS server configuration  
- Subnet mask  
- Maximum users  

** Screenshot:** `03_DHCP_Pool_Configuration.png`

---

### 4. Wireless Network SSIDs & Signal  
I configured 5 separate wireless networks (SSIDs) for Admin, Staff, Students, Guests, and IoT devices.  
I assigned these SSIDs to appropriate access points and verified connectivity and signal strength.

**Wireless Networks:**
- AdminNet
- TeachingStaffNet
- StudentNet
- GuestNet
- IoTNet

** Screenshot:** `04_Wireless_Networks_Signal.png`

---

### 5. VLAN Configuration & Status  
I implemented 6 VLANs with correct VLAN IDs and names:
- VLAN 10: Admin  
- VLAN 20: Staff  
- VLAN 30: Students  
- VLAN 40: Guest WiFi  
- VLAN 50: IoT  
- VLAN 60: Servers

All VLANs were created and verified as "active" using CLI commands.

**Screenshot:** `05_VLAN_Status_List.png`

---

### 6. Simulation in Cisco Packet Tracer  
All of the above elements were implemented in a working Packet Tracer file, including:
- Full end-to-end connectivity  
- Functional DHCP per VLAN  
- Wireless access  
- Simulated IoT cameras and smart doors  

**File:** `Holmview_Network_Design.pkt`

---

##  GitHub Portfolio Repo

[https://github.com/YOURUSERNAME/Holmview-School-Network](https://github.com/YOURUSERNAME/Holmview-School-Network)

---

## Technologies Used
- Cisco Packet Tracer
- DHCP
- VLANs & Subnetting
- Wireless Network Design
- IoT Device Simulation
- DNS/DHCP Configuration via CLI
