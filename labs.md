---
layout: default
title: Labs
---

# Coursework & Technical Labs

---
layout: default
title: Lab 1 - Raspberry Pi & Network Analysis
---

[🏠 Back to Home]({{ site.baseurl }}/)

# Lab #1: Building a Portable Network Monitor (Raspberry Pi 4)

**Objective:** To assemble a custom hardware sensor using a Raspberry Pi 4 and a 5-inch monitor to capture and analyze network traffic for security vulnerabilities.

[Raspberry Pi 4 with 5-inch monitor setup]![image](https://github.com/user-attachments/assets/aaee4321-efa0-4ff2-81d8-b0391c368cb0).![image](https://github.com/user-attachments/assets/9c198258-8c61-44a4-8609-a58e283f08f9).![image](https://github.com/user-attachments/assets/74283ae0-ec6f-452b-88c5-1be125a38f1c).![image](https://github.com/user-attachments/assets/7b80706f-c0ad-45f5-888b-de0932caaae4)

---

### 🛠️ Hardware Setup & Configuration
Instead of using a standard PC, I built a dedicated mobile station to perform network analysis:
* **Micro-Computer:** Configured a **Raspberry Pi 4 (8GB)** as the core processing unit.
* **Display Integration:** Installed a **5-inch HDMI Touch Screen** monitor for real-time visual feedback without needing a full-sized peripheral setup.
* **OS Customization:** Flashed Raspberry Pi OS and modified the `config.txt` file via the terminal to optimize resolution ($800 \times 480$) and initialize the LCD drivers.
* **Peripheral Assembly:** Mounted the cooling case and connected the GPIO pins to ensure stable power delivery to the integrated display.

### 🔍 Network Traffic Analysis (Wireshark)
Once the hardware was functional, I utilized the device to detect security threats:
* **Actions:** Captured live packets across the local network; identified unencrypted HTTP POST data packets.
* **Results:** Successfully intercepted and recovered "stolen" credentials from a simulated Man-in-the-Middle (MITM) attack.
* [cite_start]**Documentation:** Recorded how unencrypted data remains a significant risk to personal information and company details[cite: 4, 12].

### 🛡️ Mitigation Recommendations
To secure the network against the vulnerabilities discovered in this lab, I recommended:
* **Enforcing Encryption:** Transitioning all web services to **TLS 1.3**.
* **Disabling Legacy Protocols:** Turning off **LLMNR** and **NetBIOS** to prevent credential spoofing.
* [cite_start]**User Awareness:** Educating staff on the dangers of "Open" Wi-Fi and the importance of data security[cite: 2, 12].

### 💼 Professional Application (IT Support)
* **Hardware Maintenance:** This lab demonstrates my ability to assemble components, troubleshoot display drivers, and manage Linux-based systems.
* **Problem Solving:** Successfully configuring a custom 5-inch display required researching technical documentation and editing system configuration files—skills essential for Help Desk Tier 1 roles.
* **Network Visibility:** I can use this portable tool to verify network connectivity and security at the physical wall-jack level.

---
[🏠 Return to Portfolio]({{ site.baseurl }}/) | [➡️ Next Lab: Lab 2](./lab2)
---
# Lab #2: Conducting Vulnerability Scans using Nessus
**Objective:** To identify system weaknesses, analyze threat actor motivations, and understand the impact of potential data breaches.

Nessus Vulnerability Scan Dashboard <img width="1705" height="977" alt="Screenshot 2025-11-26 at 10 15 14 PM" src="https://github.com/user-attachments/assets/77e1c7b7-18a5-4d8e-8fd8-a0c5c3d17edb" />

---

### 📝 Lab Summary
This lab focused on the proactive side of cybersecurity: identifying vulnerabilities before they can be exploited. I explored how different threat actors—ranging from financially motivated cybercriminals to ideologically driven hacktivists—seek out these weaknesses to access sensitive company and customer data.

### 🛠️ Technical Implementation (Nessus)
Using the **Nessus Vulnerability Scanner**, I practiced the following security tasks:
* **Host Discovery:** Scanning the network to identify active assets and devices.
* **Vulnerability Assessment:** Running credentialed and non-credentialed scans to find outdated software and misconfigurations.
* **Risk Categorization:** Analyzing scan results to differentiate between "Critical" vulnerabilities and low-risk informational findings.
**Data Protection:** Identifying risks to essential data types, including personal information, financial reports, and company details.

### 🔑 Understanding the Threat Landscape
A key part of this lab was analyzing the motivations behind potential attacks to better prioritize defense efforts:
**Cybercriminals:** Target vulnerabilities for financial gain.
**Insider Threats:** Often motivated by discontent to exploit system weaknesses from within.
**Nation-States:** Target systems for geopolitical advantages.

### 💼 Professional Application (Help Desk / IT Support)
* **Patch Management:** I can use scan results to identify which workstations in an office need immediate security updates.
**User Education:** I can explain to users why keeping their software updated is essential for preventing cyberattacks.
***Standard Operating Procedures:** This lab introduced the importance of maintaining a secure system through consistent monitoring and awareness.

---

## Lab 3: Active Directory Lab
## 🖥️ Lab: Implementing Access Controls with Windows Active Directory
**Objective:** Configuring a Windows Server domain to manage user authentication and resource authorization.

[Active Directory Lab Screenshot] <img width="612" height="792" alt="image" src="https://github.com/user-attachments/assets/77638c83-d2cc-49ea-b0d2-84685f19f838" />


### **Lab Summary**
In this lab, I acted as a System Administrator for a simulated corporate environment. The goal was to implement a secure, scalable access control system using **Active Directory Users and Computers (ADUC)**.

### **Core Tasks Performed**
**Active Directory Hierarchy:** Created a structured environment using **Organizational Units (OUs)** to separate departments like Sales, IT, and HR.
**User Provisioning:** Created individual user accounts and assigned them to specific **Security Groups** to follow the "Principle of Least Privilege".
**Access Control Lists (ACLs):** Configured folder permissions to ensure that only authorized group members could access sensitive departmental data.

### **Professional Application (Help Desk Focus)**
This lab simulates the daily responsibilities of an IT Support Technician, including:
1. **Onboarding/Offboarding:** I am proficient in creating new user accounts and disabling access when employees leave.
2. **Permission Troubleshooting:** I can diagnose "Access Denied" errors by reviewing Group Policy and Security Group memberships.
3. **Identity Management:** I understand how AD centralizes security, making it easier to manage hundreds of users at once.
