<h1>Hi, I'm Precious! </h1>

🔹 **Network Engineer | Datacom Specialist | Cloud & Security Enthusiast**  

I have **4+ years of professional experience** in **network engineering and datacom solutions**, working with service providers and enterprise networks. My expertise spans **routing, switching, network security, automation, and cloud networking**. I’m passionate about building **resilient, scalable, and secure networks** that power modern businesses.  

---

## 🚀 About Me  

🌐 Experienced in **Cisco, Juniper, ZTE, and Huawei** environments  
🔐 Skilled in **firewall security, VPNs, IDS/IPS, and Zero Trust architecture**  
☁️ Exploring **cloud networking (AWS, Azure, GCP)** and **virtualization**  
🐍 Learning **Python for network automation**  
📡 Passionate about **network design and core networks (SGSN, GGSN, LTE, 5G)**  

---

# 🛠️ Network Tools Usage & Documentation
Here is the detailed explanations of key tools I used for daily network operations, monitoring, troubleshooting, and documentation. Each section includes **how I used the tool**, a **practical example**, and a **summary**.

---

## 1. 📌 MobaXterm

**How I used it:**  
I used MobaXterm as my main SSH and Telnet client to log into network devices for configuration and troubleshooting. On a daily basis, I relied on it for routine health checks—verifying device uptime, CPU and memory usage, checking routing tables, and ensuring configurations were properly applied.

**Practical Example:**  
I would connect to routers and switches, run diagnostic commands, and generate reports showing the health of critical infrastructure. This helped me ensure that no device was overloaded or misconfigured.

**Summary:**  
✅ MobaXterm helped me manage device configurations and perform daily system health checks efficiently.

---

## 2. 📌 Huawei NCE (Network Cloud Engine)

**How I used it:**  
I used NCE as a centralized platform to monitor Huawei nodes. This tool allowed me to track performance metrics such as CPU, memory, and storage utilization across multiple devices.

**Practical Example:**  
Each day, I generated NE (Network Element) resource utilization reports to keep track of which nodes were nearing capacity or showing abnormal behavior. This proactive monitoring helped in capacity planning and avoided potential outages.

**Summary:**  
✅ NCE gave me a clear overview of Huawei node health and supported daily utilization reporting.

---

## 3. 📌 SolarWinds

**How I used it:**  
SolarWinds was my go-to for monitoring both nodes and links in the network. It provided visibility into traffic flow, link uptime, and latency issues.

**Practical Example:**  
I created daily reports focusing on primary links, ensuring critical paths were stable and had no packet loss or latency spikes. If a primary link showed degradation, I could escalate before customers were affected.

**Summary:**  
✅ SolarWinds ensured smooth monitoring of nodes and primary links, supporting proactive fault detection.

---

## 4. 📌 Wireshark

**How I used it:**  
I used Wireshark as a packet analyzer for deep troubleshooting when facing complex issues such as packet drops, VoIP call quality problems, or unusual traffic.

**Practical Example:**  
By capturing and analyzing packets, I could identify malformed packets, jitter, retransmissions, or specific applications consuming bandwidth. This helped isolate issues faster than using device logs alone.

**Summary:**  
✅ Wireshark helped me dive deep into network traffic to troubleshoot packet-level problems.

---

## 5. 📌 Microsoft Visio

**How I used it:**  
I used Visio to design logical and physical network diagrams. These diagrams documented the infrastructure, showing device interconnections, IP addressing schemes, and failover designs.

**Practical Example:**  
When proposing new setups or troubleshooting complex environments, I presented Visio diagrams to management and team members. These visuals simplified communication and made the network easier to understand.

**Summary:**  
✅ Visio helped me document and design network layouts for better planning and communication.

---

## 📖 Final Note

These tools formed the foundation of my daily workflow in network operations. Together, they enabled me to:  
- Perform **device configuration & health checks** 🖥️  
- Monitor **nodes, links, and utilization** 📊  
- Troubleshoot **packet-level issues** 📡  
- Document **network architecture** 🗂️  

---

# 📂 Project Showcase

Here are some real-world projects where I applied the above tools:

### 🔹 Project 1: Gweru 3G Reroute Optimization
- **Tools Used:** MobaXterm, Cisco Router (Cisco ASR 1001-X), Visio.  
- **Objective:** Optimize the Gweru 3G backhaul to reduce unnecessary hops.  
- **Highlights:**  
  - Worked with TelOne after they laid fiber from HQ to Gweru 📡  
  - Configured a Cisco ASR 1001-X router to aggregate and optimize BTS site connectivity ⚙️  
  - Reduced multiple hops, improving latency and reliability for users in Gweru 🚀  

📸 *Placeholder for Visio Topology Diagram / Cisco Config Screenshot*

Sample Cisco ASR 1001-X Configuration:

cisco

---

### 🔹 Project 2: Huawei NCE Monitoring & Reporting
- **Tools Used:** Huawei NCE, SolarWinds.  
- **Objective:** Daily monitoring of Huawei core network nodes and reporting utilization.  
- **Highlights:**  
  - Generated NE (Network Element) resource utilization reports 📊  
  - Identified nodes nearing CPU/memory capacity and escalated proactively ⚠️  
  - Supported management with trend analysis for capacity planning 📈  

📸 *Placeholder for NCE Dashboard Screenshot*

---

### 🔹 Project 3: Deep Packet Analysis for Unifun
- **Tools Used:** Wireshark.  
- **Objective:** Troubleshoot Unifun’s issue of not receiving data at their server.  
- **Highlights:**  
  - Captured and analyzed packets between client and Unifun server 🔍  
  - Identified abnormal traffic patterns and missing payload delivery ❌  
  - Isolated root cause, enabling resolution and restoring service ✅  

📸 *Placeholder for Wireshark Capture Screenshot*

---


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
