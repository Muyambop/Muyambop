<h1>Hi, I'm Precious! </h1>

<h2>👨‍💻 Network Design Projects with Cisco Packet Tracer & Visio:</h2>

# 📌 Enterprise Network Design and Implementation (Packet Tracer Project)

## 📖 Overview
This project focuses on designing and implementing a hierarchical enterprise network topology using Cisco Packet Tracer.  
The goal is to configure VLANs, DHCP, HTTP, and Email servers, implement OSPF for dynamic routing, and secure device access with SSH.  
The project also tests end-to-end connectivity between departments and across VLANs.

---

## 🎯 Objectives
- Design a hierarchical network topology (core, distribution, access layers)  
- Configure VLANs per department and subnetting plan  
- Implement DHCP, HTTP, and Email servers  
- Enable OSPF routing and inter-VLAN communication  
- Secure access using SSH and port-security  
- Test connectivity and functionality (ping, traceroute, DHCP leases, server access)  

---

## 🏢 Network Scenario

The organization is distributed across **4 floors**:  

### **First Floor**
- Management – 20 PCs, 4 Printers  
- Research – 20 PCs, 4 Printers  
- Human Resource – 20 PCs, 4 Printers  

### **Second Floor**
- Marketing – 20 PCs, 4 Printers  
- Accounting – 20 PCs, 4 Printers  
- Finance – 20 PCs, 4 Printers  

### **Third Floor**
- Logistics & Store – 20 PCs, 4 Printers  
- Customer Care – 20 PCs, 4 Printers  
- Guest Area – 40 PCs, 2 Printers  

### **Fourth Floor**
- Administration – 20 PCs, 2 Printers  
- ICT – 20 PCs, 2 Printers  
- Server Room – 2 Admin PCs, 3 Servers (DHCP, HTTP, Email)  

---

## 📂 Repository Contents
- `/docs` → Full documentation  
- `/diagrams` → Network diagrams (logical + physical)  
- `/packet-tracer-files` → `.pkt` simulation files  
- `/configs` → Router, switch, and server configurations  

---

## 🖼️ Network Diagrams
Below is the topology diagram showing the bank’s Network Physical Diagram:

<p align="center">
Physical Diagram: <br/>
<img src="https://imgur.com/AIVf9Mu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Below is the topology diagram showing the bank’s Network Logical Diagram:

<p align="center">
Logical Diagram: <br/>
<img src="https://imgur.com/RVIi5hc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

  ---

## 📑 Documentation
- [📊 Download Project Presentation (PPTX)](https://files.fm/f/8khvhjezvh)

  ---
  
## 🛠️ Tools & Technologies
- Cisco Packet Tracer / GNS3  
- MS Visio / Draw.io / Visual Paradigm (for diagrams)  
- GitHub for documentation  

---

## ⚙️ Implementation Details
- **VLAN Setup**: Each department assigned its own VLAN (e.g., VLAN10, VLAN20, VLAN30)  
- **Subnetting Plan**: Based on `192.168.10.0/24` with subnets sized per department  
- **Routing**: OSPF enabled for inter-floor communication  
- **Servers**: DHCP (for dynamic IPs), HTTP, and Email hosted in the server room  
- **Security**:  
  - SSH enabled on routers for secure remote access  
  - Port security (sticky MAC, violation mode = shutdown)  
  - Console & VTY passwords, MOTD banners, and domain lookup disabled  

### 🗂️ VLAN & Subnet Allocation Table

| Department        | VLAN ID | Subnet             | Subnet Mask   | Usable IP Range       | Broadcast Address |
|-------------------|---------|--------------------|---------------|-----------------------|------------------|
| Management        | 10      | 192.168.10.0/26    | 255.255.255.192 | 192.168.10.1 – 192.168.10.62  | 192.168.10.63  |
| Research          | 20      | 192.168.10.64/26   | 255.255.255.192 | 192.168.10.65 – 192.168.10.126 | 192.168.10.127 |
| Human Resource    | 30      | 192.168.10.128/26  | 255.255.255.192 | 192.168.10.129 – 192.168.10.190 | 192.168.10.191 |
| Marketing         | 40      | 192.168.10.192/26  | 255.255.255.192 | 192.168.10.193 – 192.168.10.254 | 192.168.10.255 |
| Accounting        | 50      | 192.168.11.0/26    | 255.255.255.192 | 192.168.11.1 – 192.168.11.62   | 192.168.11.63  |
| Finance           | 60      | 192.168.11.64/26   | 255.255.255.192 | 192.168.11.65 – 192.168.11.126 | 192.168.11.127 |
| Logistics & Store | 70      | 192.168.11.128/26  | 255.255.255.192 | 192.168.11.129 – 192.168.11.190 | 192.168.11.191 |
| Customer Care     | 80      | 192.168.11.192/26  | 255.255.255.192 | 192.168.11.193 – 192.168.11.254 | 192.168.11.255 |
| Guest Area        | 90      | 192.168.12.0/25    | 255.255.255.128 | 192.168.12.1 – 192.168.12.126  | 192.168.12.127 |
| Administration    | 100     | 192.168.12.128/26  | 255.255.255.192 | 192.168.12.129 – 192.168.12.190 | 192.168.12.191 |
| ICT               | 110     | 192.168.12.192/26  | 255.255.255.192 | 192.168.12.193 – 192.168.12.254 | 192.168.12.255 |
| Server Room       | 120     | 192.168.13.0/28    | 255.255.255.240 | 192.168.13.1 – 192.168.13.14   | 192.168.13.15  |

---

## ✅ Testing & Results
- Devices in the same VLAN communicate successfully  
- Devices across different VLANs communicate through inter-VLAN routing  
- DHCP leases issued dynamically to clients  
- Successful pings and traceroutes across all floors  
- HTTP and Email server access verified  

---

## 💡 Skills Learnt
- **Network Design**: Applied hierarchical network design (core, distribution, access layers)  
- **VLAN & Subnetting**: Planned and implemented VLANs with subnetting per department  
- **Routing Protocols**: Configured OSPF for inter-floor communication  
- **Server Configuration**: Set up DHCP, HTTP, and Email servers in a simulated enterprise environment  
- **Network Security**: Implemented SSH for secure device access, port-security with sticky MAC, and password protection  
- **Simulation & Testing**: Verified connectivity with ping/traceroute, DHCP leases, and server access tests  
- **Documentation & Visualization**: Produced logical and physical topology diagrams using Visio/Draw.io and maintained structured GitHub documentation  

---


## 📌 Conclusion & Future Work
- **Achievements**: Designed and implemented a secure enterprise network with VLANs, DHCP, HTTP, Email servers, and OSPF routing. Verified end-to-end connectivity.  
## 🔮 Future Improvements
While the current design ensures reliability and scalability, the following enhancements are proposed for **enterprise-grade security and resilience**:  
🔐 **Firewalls & IDS/IPS** – Deploy firewalls and intrusion detection/prevention systems for advanced threat protection.  
🌐 **VPN Implementation** – Establish secure Virtual Private Network tunnels for remote banking and branch operations.  
☁️ **Cloud Integration** – Implement hybrid cloud for data backup, disaster recovery, and scalability.  
🛡️ **Zero Trust Security Model** – Apply stricter access control to minimize insider and external security risks.  
📊 **Network Monitoring Tools** – Use SNMP, NetFlow, and Syslog for proactive troubleshooting and performance monitoring.  
🤖 **Automation with Python & Ansible** – Automate device configuration and updates for faster, error-free management.  
🔄 **Add redundancy with HSRP/VRRP** – Configure Hot Standby Router Protocol (HSRP) or Virtual Router Redundancy Protocol (VRRP) to ensure continuous gateway availability in case of router failures.  
🌍 **Extend IPv6 addressing** – Transition to IPv6 to future-proof the network, provide larger address space, and support modern applications and IoT devices.  

---

## 📚 References
- Cisco Networking Academy – [Packet Tracer Resources](https://www.netacad.com/)  
- OSPF & VLAN configuration guides (Cisco Docs)  
- Networking textbooks & course material  


---

## 📝 Author
**Precious Muyambo**  
_Future Network Architect | Building resilient and secure digital infrastructures_  


  
<h2>👨‍💻 Network Automation Projects:</h2>
  - [Creating a comprehensive data processing tool]
  - [Build an automated security monitoring system]
  - [Integrate network management suite]


---

# 📂 Notes:

## 📂 Software-Defined Networking (SDN)  NOTES

[📑 Download the Notes (PPTX)](https://files.fm/f/jzqzbxhxtp)

## 📂 Automation with Python and PowerShell for IT and Cybersecurity NOTES

[📑 Download the Notes (PPTX)](https://files.fm/f/tkxaa5w36b)

## 📂 Cloud Computing Understanding Core Concepts NOTES
[📑 Download the Notes (PPTX)](https://files.fm/f/pfp3uwsf33)

---

<h1>Certificates:</h1>

- [Automation with Python and PowerShell for IT and Cybersecurity](https://lnkd.in/dqc8YSPW)
- [Cloud Computing: Understanding Core Concepts](https://lnkd.in/eQwYYsGt)
- [SDN and Network Function Virtualization (NFV)](https://lnkd.in/dP78CCxQ)
- [Advanced Cisco Routing: OSPF](https://lnkd.in/dManxXEw)
- [CCNA: Switching, Routing, and Wireless Essentials](https://www.credly.com/badges/eb8c04df-196e-4a4a-827a-924df77c0c0e/linked_in?t=s0x8l5)
- [Introduction to Cybersecurity](https://www.credly.com/badges/881df959-1db8-4e0a-95a0-4d9c6a2e5f54/linked_in?t=s3uz1i)
<h2> 🤳 Connect with me:</h2>

[<img align="left" alt="JoshMadakor | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]



[linkedin]: https://www.linkedin.com/in/precious-muyambo-74b60a290/



<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
