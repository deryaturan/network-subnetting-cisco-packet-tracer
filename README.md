# MIS 313 Computer Networks and Security – Network Design and Subnetting

## Student Information
Name: Derya Turan  
Student ID: 2304109020  
Izmir Democracy University  
Faculty of Economics and Administrative Sciences  
MIS 313 Computer Networks and Security  
Asst. Prof. Dr. Can Saygıner  
Submission Date: December 30, 2025  

---

## Project Description
This project presents a small-scale network design implemented using Cisco Packet Tracer. The network consists of one router and four PCs, where each PC is directly connected to a separate FastEthernet interface on the router.

The main purpose of the project is to demonstrate subnetting by dividing the 192.168.20.0/24 network into four /26 subnets and ensuring successful communication between all devices through proper IP addressing and router configuration.

---

## Network Structure
- 1 Router  
- 4 PCs  
- Each PC connected to a separate router interface  
- Each interface represents a different subnet  
- Router acts as the central device enabling inter-subnet communication  

---

## Subnetting Design
The 192.168.20.0/24 network is divided into four equal /26 subnets:

Subnet 1: 192.168.20.0/26  
Subnet 2: 192.168.20.64/26  
Subnet 3: 192.168.20.128/26  
Subnet 4: 192.168.20.192/26  

Each subnet provides 62 usable IP addresses and has its own default gateway configured on the router.

---

## IP Address Configuration

PC0: 192.168.20.2 /26  Gateway: 192.168.20.1  
PC1: 192.168.20.66 /26  Gateway: 192.168.20.65  
PC2: 192.168.20.130 /26  Gateway: 192.168.20.129  
PC3: 192.168.20.194 /26  Gateway: 192.168.20.193  

---

## Configuration Summary
- Router interfaces were manually configured using Cisco CLI  
- Each interface was assigned an IP address according to the subnet plan  
- Interfaces were enabled to ensure connectivity  
- Routing between subnets was handled automatically via directly connected routes  
- Configuration was verified using:
  - show ip interface brief  
  - show ip route  

---

## Testing
Ping tests were performed between all PCs to verify connectivity.  
All devices successfully communicated with each other across different subnets.

This confirms that:
- IP addressing is correct  
- Subnetting is correctly implemented  
- Router configuration is working properly  
- Network connectivity is fully established  

---

## Screenshots
The screenshots folder contains:
- Network topology view  
- IP configuration screens  
- Router CLI configuration  
- Ping test results  

---

## Files in Repository
- 2304109020.cisco.pkt (Packet Tracer project file)  
- 2304109020.cisco.docx (Full written report)  
- screenshots/ (Network proof images)  

---

## Conclusion
This project successfully demonstrates subnetting and basic router configuration in a Cisco Packet Tracer environment. The network is properly segmented into four subnets, and full communication between all devices is achieved.
