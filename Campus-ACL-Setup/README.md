# 🌐 Campus Network Security using ACL (Access Control Lists)

## 📌 Project Overview
This project focuses on implementing **Access Control Lists (ACLs)** to enhance security in a campus network.  
The goal is to control and filter network traffic between different departments such as HR, Admin, and Students.

---

## 🎯 Objectives
- Restrict unauthorized access between departments  
- Allow only specific traffic based on IP and port  
- Improve overall network security  
- Monitor and control data flow  

---

## 🛠️ Tools & Technologies
- Cisco Packet Tracer  
- Networking Concepts (TCP/IP, VLAN, Routing)  
- Access Control Lists (Standard & Extended ACL)  

---

## 🏗️ Network Design
- Multiple departments (HR, Admin, Students)  
- VLAN-based segmentation  
- Router configured for inter-VLAN routing  
- ACL applied to control traffic flow  

---

## 🔐 ACL Implementation

### ✅ Standard ACL
- Used to filter traffic based on **source IP address**  
- Example:
  - Block Students network from accessing Admin network  

---

### ✅ Extended ACL
- Used to filter traffic based on:
  - Source IP  
  - Destination IP  
  - Protocol (TCP/UDP)  
  - Port number  

- Example:
  - Allow HTTP (port 80)  
  - Block FTP (port 21)  

---

## ⚙️ Configuration Steps
1. Create VLANs for each department  
2. Assign IP addresses using subnetting  
3. Configure router for inter-VLAN routing  
4. Apply Standard ACL to restrict basic access  
5. Apply Extended ACL for advanced filtering  
6. Test connectivity using ping and simulation mode  

---

## 🧪 Testing & Validation
- Verified communication between allowed networks  
- Blocked unauthorized access using ACL rules  
- Used ping and simulation tools for testing  

---

## 📊 Results
- Improved network security  
- Controlled access between departments  
- Efficient traffic management  

---

## 📁 Files Included
- Cisco Packet Tracer file (.pkt)  
- Network topology screenshots  
- Configuration details  

---

## 🚀 Conclusion
This project demonstrates how ACLs can be used to **secure a campus network** by controlling traffic flow and preventing unauthorized access.

---

## 📫 Contact
- Email: smrithi06.s@gmail.com  
- GitHub: https://github.com/yourusername  

---

⭐ *This project showcases practical implementation of network security using ACLs*
