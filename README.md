# AZ-104 Lab 06 – Implement Network Traffic Management

## 📌 Project Overview
This project is a hands-on implementation of **Azure Network Traffic Management** based on **AZ-104: Microsoft Azure Administrator – Lab 06**.

The objective of this lab is to configure and manage **network traffic flow** using **Azure Load Balancer** and **Network Security Groups (NSGs)** to ensure **high availability and secure access** to virtual machines.

---

## 🎯 Objectives
- Implement Azure network traffic management
- Configure Azure Load Balancer
- Manage inbound and outbound traffic using NSGs
- Validate traffic flow and high availability
- Document the implementation with screenshots

---

## 🛠️ Azure Services Used
- Azure Virtual Network (VNet)
- Subnets
- Virtual Machines (Windows/Linux)
- Azure Load Balancer (Standard)
- Network Security Groups (NSG)
- Public IP Address

---

## 🧱 Architecture Overview
- Multiple VMs deployed in the same Virtual Network
- Azure Load Balancer distributes incoming traffic
- NSG rules control inbound and outbound access
- Health probes monitor VM availability

---

## ⚙️ Implementation Steps
1. Created a Virtual Network and Subnets  
2. Deployed multiple Virtual Machines  
3. Created and configured a Standard Load Balancer:
   - Frontend IP configuration  
   - Backend pool  
   - Health probe  
   - Load balancing rule  
4. Configured Network Security Group rules:
   - Inbound rules (HTTP / SSH / RDP as required)  
   - Outbound rules  
5. Tested traffic distribution and VM accessibility  
6. Documented the complete process with screenshots  

---

## ✅ Outcome
- Successfully implemented traffic distribution across VMs
- Verified secure access using NSG rules
- Achieved high availability using Azure Load Balancer
- Gained hands-on experience with Azure networking concepts

---

## 📄 Documentation
**PDF Documentation:**  
`AZ-104_Lab06_Implement_Network_Traffic_Management.pdf`  
(Includes step-by-step execution and screenshots)

---

## 📚 Skills Demonstrated
- Azure Networking
- Load Balancer configuration
- Network Security Groups (NSG)
- Traffic flow management
- Azure Administrator (AZ-104) hands-on experience

---

## 🧠 Certification Mapping
- AZ-104: Microsoft Azure Administrator  
- Module: Implement and manage virtual networking

---

## 👤 Author
**Ankith Ajith Kumar**  
Cloud | Azure | DevOps Enthusiast

---

## ⭐ Notes
This project is created for learning and certification preparation purposes.
