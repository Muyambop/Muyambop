<h1>Hi, I'm Precious! </h1>

🔹 **Network Engineer | IT Administrator | Cloud & Security Enthusiast**  

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



## 📖 Final Note

These tools formed the foundation of my daily workflow in network operations. Together, they enabled me to:  
- Perform **device configuration & health checks** 🖥️  
- Monitor **nodes, links, and utilization** 📊  
- Troubleshoot **packet-level issues** 📡  
- Document **network architecture** 🗂️  


---

# 🧰 Tools & Technologies Used 
---

## ☁️ Microsoft Azure Free Account
- **Purpose:** Cloud hosting platform for creating and managing virtual machines and services.  
- **Usage:**
  - Created a **free-tier account** to deploy the Windows Server VM.
  - Managed resources using the **Azure Portal**.
  - Integrated with **Microsoft Defender for Cloud** to visualize real-time attacks.
  - Simulated real-world attack exposure by keeping RDP and HTTP ports open.

---

## 🖥️ Windows Server VM
- **Purpose:** Acts as the **target system** for simulated attacks from the internet.
- **Usage:**
  - Deployed using **Azure Virtual Machines** service.
  - Configured with **public IP** and open **RDP (3389)** for remote access.
  - Observed attacks (e.g., brute-force, port scanning) in the **Azure Attack Map**.

---

## 🌐 Azure Portal
- **Purpose:** Central **management console** for Azure services.
- **Usage:**
  - Created and configured **VMs**, **Network Security Groups**, and **Defender for Cloud**.
  - Viewed **security alerts**, **attack sources**, and **performance metrics**.
  - Used **dashboard visualizations** to monitor real-time attack data.

---

## 🛡️ Microsoft Defender for Cloud
- **Purpose:** Provides **threat protection**, **vulnerability assessment**, and **security posture** insights.
- **Usage:**
  - Enabled on the subscription to monitor exposed ports and suspicious activity.
  - Displayed **Attack Map** showing geographic sources of attacks.
  - Generated **security alerts** for RDP brute-force attempts and malware scans.

---

## 🌍 Azure Attack Map
- **Purpose:** **Visual tool** that displays real-time attack telemetry from exposed resources.
- **Usage:**
  - Monitored inbound attack attempts on the **Windows VM**.
  - Showed **attacker IPs**, **locations**, and **attack types**.
  - Provided visibility into **global threat activity** affecting the lab.

---

## 🔑 RDP (Remote Desktop Protocol)
- **Purpose:** Remote management interface for Windows servers.
- **Usage:**
  - Used to **log into** the Windows Server VM from a local workstation.
  - Exposed **TCP port 3389** to simulate attack surface.
  - Observed frequent **brute-force attempts** from global sources.

---

## 🧰 Microsoft 365 & Active Directory Administration
- **Purpose:** Centralized **identity and access management** and integration with Azure.
- **Usage:**
  - Integrated **Azure Active Directory** to manage VM user authentication.
  - Demonstrated how exposed accounts become targets for **credential attacks**.
  - Reinforced importance of **MFA** and **role-based access**.

---

## 🔥 Juniper Firewall & VPN Configuration
- **Purpose:** Perimeter security and secure remote connectivity.
- **Usage:**
  - (In extended enterprise setups) used to **restrict traffic** and **segment networks**.

---

## 🌐 Network Design & Troubleshooting (TCP/IP, DNS, DHCP, Routing, Switching)
- **Purpose:** Ensures reliable connectivity and traffic flow between cloud and local environments.
- **Usage:**
  - Configured **public IP**, **DNS resolution**, and **routing** for Azure VM.
  - Used **TCP/IP analysis** to identify open ports targeted by attackers.
  - Troubleshot network reachability and latency for remote RDP connections.

---

## 🧱 Virtualization: VMware, Hyper-V
- **Purpose:** Local **simulation and testing** environments for comparison.
- **Usage:**
  - Used **VMware/Hyper-V** to build local test labs.

---

## 🧰 IT Security & Compliance (Firewalls, IDS/IPS, Antivirus, Security Audits)
- **Purpose:** Establish **layered security** around exposed cloud resources.
- **Usage:**
  - Implemented **Azure NSGs** (Firewall equivalent) to control inbound traffic.
  - Enabled **Defender for Cloud** (IDS/IPS features) for threat detection.
  - Reviewed **security recommendations** and compliance alerts.
  - Simulated **vulnerability assessments** on exposed services.

---

## ⚙️ IT Process Automation (PowerShell, Python)
- **Purpose:** Automate deployment, configuration, and security analysis.
- **Usage:**
  - Used **PowerShell** commands to:
    - Create  VMs

---

## 💾 Backup & Disaster Recovery Planning
- **Purpose:** Protect critical data and maintain business continuity.
- **Usage:**
  - Configured **Azure Backup** for VM snapshots.
  - Showed how frequent attacks reinforce need for **automated restore points**.
  - Demonstrated **disaster recovery** via redeploying VMs from backups.

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

- This picture below captures me during the **Gweru 3G Reroute Project**, where I was responsible for optimizing and redesigning the network path to improve efficiency and performance

<p align="center">
Network Engineer optimizing and redesigning the network path: <br/>
<img src="https://imgur.com/erwARiG.png" alt="Gweru 3G Project" width="80%" height="80%">
<br />
 


## 🔧 Challenge  
The original design had **multiple unnecessary hops**, leading to higher latency and reduced reliability.  


## 📡 Solution  
- Collaborated with **TelOne**, who laid **fiber from HQ to Gweru**  
- Configured a **Cisco switch cluster** to aggregate and manage traffic for BTS sites in the region  


## 🚀 Outcome  
- ✅ Reduced latency  
- ✅ Improved redundancy  
- ✅ Scalable support for **3G services** in Gweru  


✨ This project demonstrates my hands-on expertise in **network optimization, ISP collaboration, and datacom engineering**.  


## Tools used: 
Below are the tools used:

<p align="center">
 MobaXterm: <br/>
<img src="https://imgur.com/kFwbURu.png" alt="Gweru 3G Project" width="80%" height="80%">
<br />
 

<p align="center">
  Visio: <br/>
<img src="https://imgur.com/G9N4hTt.png" height="80%" width="80%" alt="Gweru 3G Project"/>
<br />


---

### 🔹 Project 2: Huawei NCE Monitoring & Reporting
- **Tools Used:** Huawei NCE, SolarWinds.  
- **Objective:** Daily monitoring of Huawei core network nodes and reporting utilization.  
- **Highlights:**  
  - Generated NE (Network Element) resource utilization reports 📊  
  - Identified nodes nearing CPU/memory capacity and escalated proactively ⚠️  
  - Supported management with trend analysis for capacity planning 📈  

<p align="center">
 NCE: <br/>
<img src="https://imgur.com/pJFsrci.png" alt="Huawei NCE Monitoring" width="80%" height="80%">
<br />

 

<p align="center">
  Resource Utilization Report: <br/>
<img src="https://imgur.com/YDbEeOx.png" height="80%" width="80%" alt="Reporting"/>
<br />



<p align="center">
 Solarwinds: <br/>
<img src="https://imgur.com/BsUN8s7.png" alt="Solawinds Monitoring" width="80%" height="80%">
<br />

 

<p align="center">
Primary links Report: <br/>
<img src="https://imgur.com/itNPs8q.png" height="80%" width="80%" alt="Reporting"/>
<br />


<p align="center">
Healthy Checks Report: <br/>
<img src="https://imgur.com/PVpY0JS.png" height="80%" width="80%" alt="Reporting"/>
<br />

---

### 🔹 Project 3: Deep Packet Analysis for Unifun
- **Tools Used:** Wireshark.  
- **Objective:** Troubleshoot Unifun’s issue of not receiving data at their server.  
- **Highlights:**  
  - Captured and analyzed packets between client and Unifun server 🔍  
  - Identified abnormal traffic patterns and missing payload delivery ❌  
  - Isolated root cause, enabling resolution and restoring service ✅  

<p align="center">
  Visio: <br/>
<img src="https://imgur.com/i1UzodH.png" height="80%" width="80%" alt="Gweru 3G Project"/>
<br />


---
#  Project 4: Active Directory Lab with DHCP, NAT, and Client Setup

This project demonstrates the setup of an **Active Directory Domain Controller (DC)** with DHCP, NAT, and client integration using **Server 2019** and **Windows 10** inside **VirtualBox** or **VMware**. The lab simulates a small enterprise network with Internet connectivity and centralized management.

---

## 📌 Project Overview

- **Domain Controller (Server 2019)** configured with:
  - Active Directory Domain Services (AD DS)
  - DNS
  - DHCP
  - NAT/Routing
- **Client (Windows 10)** joined to the domain.
- **PowerShell automation** used to create **+1k test users** in Active Directory.
- **Internet access** provided to internal clients via NAT.

---

## 🖥️ Lab Setup

### Virtual Machines
- **DC (Server 2019)**  
  - NIC 1 (Internet): Gets DHCP from home router  
  - NIC 2 (Internal): Static IP `172.16.0.1`  
  - Roles: AD DS, DNS, DHCP, NAT
- **Client1 (Windows 10)**  
  - NIC (Internal): Gets IP from DC via DHCP  
  - Domain-joined to `mydomain.com`

---

## 🌐 Network Configuration

### Domain Controller (Server 2019)
- **Internal NIC**  
  - IP: `172.16.0.1`  
  - Subnet Mask: `255.255.255.0`  
  - DNS: `127.0.0.1`  

- **DHCP Scope**  
  - Range: `172.16.0.100 – 172.16.0.200`  
  - Subnet Mask: `255.255.255.0`  
  - Gateway: `172.168.0.1`  
  - DNS: `172.16.0.1`  

### Client1 (Windows 10)
- NIC (Internal): Receives DHCP from DC  
- Domain: `mydomain.com`  

---

## ⚡ Features
- Centralized **Active Directory domain** for authentication.  
- **DHCP** for automatic IP assignment.  
- **DNS** for domain resolution.  
- **NAT/RAS** to allow internal clients access to the Internet.  
- **PowerShell scripting** to bulk-create users (+1,000 test accounts).  

---

## 🔧 Requirements
- Virtualization software (VirtualBox or VMware).  
- **Windows Server 2019 ISO**.  
- **Windows 10 ISO**.  

---

## 🚀 How to Run
1. Install **Server 2019** VM with 2 NICs (Internet + Internal).  
2. Configure static IP on internal NIC (`172.16.0.1`).  
3. Install and configure AD DS, DNS, DHCP, and NAT.  
4. Create domain `mydomain.com`.  
5. Install **Windows 10** VM, connect it to the Internal network, and join it to the domain.  
6. Use provided **PowerShell script** to create test users.  

---

## 📜 Notes
- Ensure **Internal network** is only for domain communication.  
- NAT is required for client Internet access.  
- Adjust DHCP scope and DNS as per lab environment.  

---

## 📷 Diagram

<p align="center">
 Network Diagram: <br/>
<img src="https://imgur.com/9DHIAG7.png" alt="Network Diagram" width="80%" height="80%">
<br />
  
---


<p align="center">
 DC: <br/>
<img src="https://imgur.com/a3XwBqD.png" alt="DC" width="80%" height="80%">
<br />

 <p align="center">
 Internal NIC: <br/>
<img src="https://imgur.com/Kjcxk0V.png" alt="internal NIC" width="80%" height="80%">
<br /


   <p align="center">
 Active Directory: <br/>
<img src="https://imgur.com/LqhxFB5.png" alt="AD" width="80%" height="80%">
<br /

 <p align="center">
 Organizational Unit: <br/>
<img src="https://imgur.com/kYty2yw.png" alt="Organizational Unit" width="80%" height="80%">
<br /

<p align="center">
Scope: <br/>
<img src="https://imgur.com/lxU7aYg.png" alt="New scope" width="80%" height="80%">
<br /



<p align="center">
IP address range: <br/>
<img src="https://imgur.com/37yco7c.png" alt="IP address range" width="80%" height="80%">
<br /
  
<p align="center">
Default gateway: <br/>
<img src="https://imgur.com/ufmiHjA.png" alt="Default gateway" width="80%" height="80%">
<br /


<p align="center">
NAT: <br/>
<img src="https://imgur.com/dfFuymM.png" alt="NAT" width="80%" height="80%">
<br /

<p align="center">
DNS: <br/>
<img src="https://imgur.com/JcEK0yh.png" alt="DNS" width="80%" height="80%">
<br /

<p align="center">
PowerShell: <br/>
<img src="https://imgur.com/9VvKzwo.png" alt="PowerShell" width="80%" height="80%">
<br /

<p align="center">
Users: <br/>
<img src="https://imgur.com/3pQdSxr.png" alt="Users" width="80%" height="80%">
<br /


  <p align="center">
Client1: <br/>
<img src="https://imgur.com/EDa7DCk.png" alt="Client1" width="80%" height="80%">
<br /

    
  <p align="center">
Test connectivity : <br/>
<img src="https://imgur.com/gVwXTZB.png" alt="Test connectivity " width="80%" height="80%">
<br /
---


## 👤 Author
- Precious Muyambo  
- [GitHub Profile](https://github.com/Muyambop) 

---
## References  

1. Microsoft Docs. (2024). *Active Directory Domain Services Overview.* Retrieved from [https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview)  

2. Microsoft Docs. (2024). *Install a new Active Directory forest.* Retrieved from [https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/deploy/install-a-new-active-directory-forest](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/deploy/install-a-new-active-directory-forest)  

3. Microsoft Docs. (2023). *DHCP Server Role in Windows Server.* Retrieved from [https://learn.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-top](https://learn.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-top)  

4. Microsoft Docs. (2023). *Configure NAT with Windows Server.* Retrieved from [https://learn.microsoft.com/en-us/windows-server/remote/remote-access/nat/](https://learn.microsoft.com/en-us/windows-server/remote/remote-access/nat/)  

5. VMware Docs. (2024). *Using VMware Workstation for Windows Server Labs.* Retrieved from [https://docs.vmware.com](https://docs.vmware.com)  

6. Oracle VM VirtualBox Manual. (2024). *Networking in VirtualBox.* Retrieved from [https://www.virtualbox.org/manual/ch06.html](https://www.virtualbox.org/manual/ch06.html)  

7. Microsoft Tech Community. (2023). *Best Practices for Domain Controller Deployment.* Retrieved from [https://techcommunity.microsoft.com](https://techcommunity.microsoft.com)  

8. Gibson, D. (2022). *Managing and Maintaining a Microsoft Windows Server Environment.* Wiley Publishing.  

9. Minasi, M. (2019). *Mastering Windows Server 2019.* Sybex Publishing.  

10. Pluralsight. (2024). *Active Directory & Windows Server Administration Courses.* Retrieved from [https://www.pluralsight.com](https://www.pluralsight.com)  

---


#  Project 5: 🧱 SafeLine WAF Home Lab 

This repository contains a **complete cybersecurity home lab** demonstrating how to deploy and secure a vulnerable web application using **SafeLine Web Application Firewall (WAF)**.

The project showcases how to:
- Host a vulnerable web app (**DVWA**) on **Ubuntu Server** using a **LAMP stack**
- Launch **SQL Injection attacks** from **Kali Linux**
- Protect the application using **SafeLine WAF**
- Configure advanced WAF features like **HTTP Flood Defense**, **Authentication Sign-In**, and **Custom Deny Rules**

---

## ⚙️ Project Components

| Component      | Purpose                                      |
|----------------|----------------------------------------------|
| **VirtualBox** | Virtualization platform for running VMs       |
| **Ubuntu Server** | Hosts the DVWA web app                     |
| **Kali Linux** | Attack simulation and testing                 |
| **DVWA**       | Vulnerable Web Application                   |
| **SafeLine WAF** | Web Application Firewall protection layer   |
| **LAMP Stack** | Backend environment (Apache, MySQL, PHP)     |

---

## 🚀 Setup Summary

1. **Install VirtualBox** and create two VMs:
   - **Ubuntu Server (22.04 LTS)**
   - **Kali Linux**

2. **Configure Ubuntu Server**:
   - Install LAMP stack  
   - Deploy **DVWA**
   - Configure **MySQL** and **Apache** (port 8080)
   - Add local DNS: `dvwa.local`

3. **Generate SSL Certificate**:
   ```bash
   sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 \
   -keyout /etc/ssl/dvwa/dvwa.key -out /etc/ssl/dvwa/dvwa.crt

## 🧪 Step 4: Test Security

Use **Kali Linux** to simulate attacks and validate SafeLine WAF’s protection.

### 🧠 SQL Injection Test
1. Open a browser in **Kali Linux** and navigate to:
https://dvwa-waf.local


2. Log in to **DVWA**:
Username: admin
Password: password

3. Set **Security Level** to **Low** in DVWA.
4. Navigate to the **SQL Injection** module.
5. Perform a sample injection in the input field:
admin' OR '1'='1


6. ✅ **Expected Result:**  
- The **SafeLine WAF** detects and blocks the malicious SQLi attempt.  
- The request is logged and denied access to the backend.

7. 🔍 **Verification:**  
- Check WAF logs in the SafeLine dashboard to confirm the block.  
- You may see an alert or blocked request entry.

---

## 🔐 WAF Features Demonstrated

| Feature | Description |
|----------|-------------|
| ✅ **SQL Injection Protection** | Detects and blocks SQLi attacks in real time. |
| ✅ **HTTP Flood / DoS Defense** | Limits high-frequency requests to prevent denial of service. |
| ✅ **Authentication Gateway** | Adds login verification before backend access. |
| ✅ **IP Blocking (Custom Deny Rules)** | Allows administrators to manually block attacker IPs. |

These features showcase SafeLine WAF’s ability to **detect**, **prevent**, and **log** web-based attacks while ensuring legitimate traffic is not disrupted.

---

## 🧠 Key Skills Learned

Through this lab, you develop hands-on experience with:

- 🧰 **Virtualization & Networking** — Configuring VMs with bridged adapters  
- 🐧 **Linux Server Administration** — Managing Ubuntu and services  
- 🌐 **Web Application Security** — Deploying and testing DVWA  
- 🧱 **WAF Configuration & Management** — Installing and tuning SafeLine  
- 🔐 **SSL/TLS Certificate Setup** — Enabling secure HTTPS traffic  
- 💉 **SQL Injection Testing** — Launching and analyzing attacks  
- 🌍 **DNS & Reverse Proxy Concepts** — Mapping local domains and traffic flow

---

## 📚 References

- [🔗 SafeLine WAF Official Website](https://waf.chaitin.com)  
- [🔗 DVWA GitHub Repository](https://github.com/digininja/DVWA)  
- [🔗 VirtualBox Download Page](https://www.virtualbox.org/wiki/Downloads)  
- [🎥 YouTube Tutorial Guide](https://youtu.be/N0dEC1nuWCQ)

---

## 🧠 Summary

This lab demonstrates a **complete web application defense workflow**:

1. Deploy a vulnerable web app (**DVWA**).  
2. Launch real-world attacks using **Kali Linux**.  
3. Protect and monitor the application using **SafeLine WAF**.

By simulating **offensive and defensive** cybersecurity practices, learners gain a practical understanding of **how WAFs detect and mitigate common threats** such as **SQL Injection**, **DoS**, and **unauthorized access**.

This project bridges the gap between **penetration testing** and **secure web infrastructure engineering**, providing valuable skills for **cybersecurity professionals**.




---

#  Project 6: 🧱 Windows VM Attack Map — Microsoft Azure Free Account

This project demonstrates how to **deploy a Windows Virtual Machine (VM)** on a **Microsoft Azure Free Account**, expose it to the internet, and visualize **real-world cyber attacks** using the **Azure Security Center Attack Map**.

The lab provides hands-on experience in **cloud security monitoring**, **attack detection**, and **threat visualization** within the Azure environment.

---

## 🧠 Project Overview

You will learn how to:
- Set up a **Windows Server VM** using the **Azure Free Tier**
- Configure **public network access** to simulate real-world exposure
- Enable **Microsoft Defender for Cloud**
- View **live attack data** on the **Azure Attack Map**
- Understand **common attack patterns** (RDP brute force, port scanning, malware attempts)

---

## 🧰 Tools & Services Used

| Tool / Service | Purpose |
|----------------|----------|
| **Microsoft Azure Free Account** | Cloud environment |
| **Windows Server VM** | Target for attack simulation |
| **Azure Portal** | Management interface |
| **Microsoft Defender for Cloud** | Security monitoring and protection |
| **Azure Attack Map** | Visual representation of attack sources |
| **RDP (Remote Desktop Protocol)** | Remote access interface often targeted by attackers |

---

## ⚙️ Step-by-Step Setup

### 1. 🪟 Create a Microsoft Azure Free Account
- Go to [https://azure.microsoft.com/free](https://azure.microsoft.com/free)
- Sign up using your email, phone, and payment method (no charges during free tier)
- You’ll receive **$200 credit** for 30 days and **12 months of free services**

---

### 2. 🧱 Create a Windows Virtual Machine
1. Navigate to **Azure Portal** → **Virtual Machines** → **Create**
2. Select:
   - **Image**: Windows Server 2022 Datacenter
   - **Size**: Standard B1s (free tier eligible)
   - **Username**: `azureadmin`
   - **Password**: choose a strong one
3. Under **Inbound Ports**, select:
   - ✅ **RDP (3389)**
   - ✅ **HTTP (80)**
4. Click **Review + Create** → **Create**

---

### 3. 🌐 Configure Networking
- VM will have a **Public IP** assigned
- Open **Networking** tab
- Ensure **RDP (TCP/3389)** and **HTTP (TCP/80)** are open
- (Optional) Add port **445** or **22** to attract more attacks (⚠️ for testing only)

---

### 4. 🛡️ Enable Microsoft Defender for Cloud
1. In Azure Portal, search **Defender for Cloud**
2. Enable it for your subscription
3. Turn on **Enhanced Security Features**
4. Enable **Microsoft Defender for Servers**

---

### 5. 🌍 View Attack Map
1. Wait **12–24 hours** after exposing the VM publicly
2. Go to **Microsoft Defender for Cloud → Security Alerts**
3. Select **Attack Map** visualization
4. Observe:
   - Source countries
   - Attack types (RDP brute force, port scanning)
   - Frequency and timestamps

---

### 6. 📊 Monitor and Analyze
- Review **Security Alerts**
- Identify attacker IPs, geolocation, and methods
- Learn how **attack surface exposure** invites malicious activity

---

## 🔐 Security Best Practices (After Testing)

Once you finish the experiment:
- Disable or delete the VM
- Close all inbound ports
- Use **Network Security Groups (NSG)** with limited access
- Implement **Just-In-Time (JIT)** access for RDP
- Enable **Multi-Factor Authentication (MFA)** for Azure login

---

## 🧾 Skills Demonstrated

- ☁️ **Cloud Infrastructure Setup (Azure)**
- 🧱 **Windows Server Configuration**
- 🌍 **Public Network Exposure & Attack Simulation**
- 🔍 **Threat Detection and Analysis**
- 🧠 **Understanding Brute Force and Reconnaissance Attacks**
- 🛡️ **Cloud Security Center Monitoring**

---

## 📚 References

- [Microsoft Azure Free Account](https://azure.microsoft.com/free)  
- [Microsoft Defender for Cloud Docs](https://learn.microsoft.com/en-us/azure/defender-for-cloud)  
- [Azure Attack Map Overview](https://portal.azure.com)  
- [Windows Server 2022 Image](https://learn.microsoft.com/en-us/windows-server/get-started/whats-new-windows-server-2022)

---

## 🧠 Summary

This project demonstrates how **exposing a Windows VM to the public internet** leads to real-world attack attempts, visible through Azure’s **Attack Map**.  
It provides practical insights into:
- How attackers discover vulnerable endpoints
- Why **defensive monitoring** and **secure configuration** are essential
- The importance of **cloud-native security tools** like **Defender for Cloud**

By completing this lab, you’ll gain a deeper understanding of **cloud attack surfaces** and **threat visibility** in **Microsoft Azure**.

---



<h2>👨‍💻 Network Design Projects with Cisco Packet Tracer & Visio:</h2>

#  Project 7: 📌 Enterprise Network Design and Implementation (Packet Tracer Project)

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
