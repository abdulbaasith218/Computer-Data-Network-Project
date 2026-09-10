# Designing a Scalable & Secure Network for the Faculty of Engineering

## 📌 Project Overview

This project was developed as part of the **EC4060 - Computer and Data Networking** module. The objective was to design a **scalable, secure, and efficient network infrastructure** for the Faculty of Engineering.

The proposed network architecture focuses on effective IP address management, subnet allocation, access control, security policies, and resource management while allowing future expansion.

---

# 🎯 Project Objectives

The main objectives of this project were:

- Design a structured network infrastructure for the Faculty of Engineering.
- Allocate dedicated subnets for different departments and administrative sections.
- Ensure scalability with sufficient future growth capacity.
- Implement security policies using access restrictions.
- Configure DHCP for dynamic IP address allocation.
- Control access to shared resources such as printers and CCTV systems.

---

# 🏢 Network Design Structure

The network was designed for the following sections:

### Academic Departments

- Civil Engineering Department
- Mechanical Engineering Department
- Electrical & Electronic Engineering (EEE) Department
- Computer Engineering Department
- Interdisciplinary Studies Department

### Administrative Section

- Faculty Administration Network

Each section was assigned a dedicated subnet to improve:

- Network management
- Security isolation
- Performance
- Future scalability

---

# 🔢 Subnet Allocation

The subnet design includes:

- Unique subnet allocation for each department.
- Defined subnet masks.
- Usable host address ranges.
- Broadcast addresses.
- Minimum **30% future expansion capacity** for each network segment.

This ensures that additional devices can be added without redesigning the entire network.

---

# 🖥️ Network Segmentation

Each department was divided into separate networks:

## Staff Network

Used by:

- Academic staff
- Department administrators

Access:

✅ Department resources  
✅ Department printers  
✅ Shared devices  


## Student Network

Used by:

- Undergraduate students
- Laboratory users

Access:

✅ Internet access  
✅ Learning resources  

Restricted from accessing confidential staff resources.

---

# 🔐 Security & Access Control Mechanisms

## Departmental Access Control

- Staff users can only access their respective department's student network.
- Unauthorized access between departments is restricted.

---

## Printer & Shared Device Security

- Department printers and shared resources are accessible only by authorized staff members.
- Student networks are prevented from accessing restricted devices.

---

## CCTV Network Security

A centralized CCTV network was designed:

- Dedicated subnet for all CCTV cameras.
- Camera traffic isolated from normal user networks.
- Only two authorized administrator computers can access CCTV monitoring systems.

---

# 🌐 DHCP Configuration

A DHCP server was configured to automatically assign IP addresses to network devices.

Benefits:

- Reduces manual IP configuration.
- Minimizes IP addressing errors.
- Improves network administration efficiency.

Configured features:

- DHCP address pools
- Default gateway assignment
- DNS server configuration
- Automatic client IP allocation

---

# 🛠️ Technologies & Concepts Used

- IPv4 Addressing
- Subnetting
- Variable Length Subnet Masking (VLSM)
- DHCP Configuration
- Network Security Policies
- Access Control
- Network Segmentation
- IP Address Management


---

# 📊 Expected Outcomes

The designed network provides:

✅ Improved network organization  
✅ Enhanced security through segmentation  
✅ Efficient IP address management  
✅ Controlled resource accessibility  
✅ Support for future network expansion  

---

# 🚀 Future Improvements

Possible improvements include:

- Implementation of VLAN-based segmentation.
- Firewall integration.
- Wireless network expansion.
- Network monitoring system deployment.
- Intrusion Detection and Prevention System (IDS/IPS).

---

# 👨‍💻 Author

**Kilurudeen Abdul Baasith**

BSc Engineering (Hons)  
Electrical & Electronic Engineering  
University of Jaffna

---

# 📚 Module

**EC4060 - Computer and Data Networking**
