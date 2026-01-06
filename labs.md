---
layout: default
title: Labs
---
# 🛠️ Technical Labs & Projects
[🏠 Back to Home](index.md)

# Lab #1: Building a Portable Network Monitor (Raspberry Pi 4)

**Objective:** To assemble a custom hardware sensor using a Raspberry Pi 4 and a 5-inch monitor to capture and analyze network traffic for security vulnerabilities.

[Raspberry Pi 4 with 5-inch monitor setup]

![image](https://github.com/user-attachments/assets/aaee4321-efa0-4ff2-81d8-b0391c368cb0).
![image](https://github.com/user-attachments/assets/9c198258-8c61-44a4-8609-a58e283f08f9).
![image](https://github.com/user-attachments/assets/74283ae0-ec6f-452b-88c5-1be125a38f1c).
![image](https://github.com/user-attachments/assets/7b80706f-c0ad-45f5-888b-de0932caaae4)

---

### 🛠️ Hardware Setup & Raspbian OS Configuration
I built a mobile hardware station designed for field testing and network connectivity:
* **Micro-Computer:** Utilized a **Raspberry Pi 4 (8GB)** as the core processing unit.
* **Operating System:** Flashed and configured **Raspbian**, a Debian-based Linux distribution optimized for the Pi.
* **Integrated Display:** Successfully mounted a **5-inch HDMI Touch Screen** and modified the `config.txt` file to set the optimal $800 \times 480$ resolution.

### 📶 Wireless LAN Connectivity (Hotspot Integration)
The primary technical challenge was establishing a network connection with the Professor's mobile hotspot using terminal commands:
* **CLI Configuration:** Accessed the Raspbian terminal to edit the `wpa_supplicant.conf` file, manually defining the SSID and WPA2-PSK credentials.
* **Network Verification:** Used `iwconfig` to confirm the wireless association and `ifconfig` to verify that a valid IP address was assigned via DHCP.
* **Connectivity Testing:** Used `ping` to verify successful routing between the Pi, the hotspot, and the external internet.

### 🛡️ Security & Awareness (CIS 165 Integration)
Applying the principles of security awareness to this hardware build
**Data Protection:** Recognized that sensitive data (personal, financial, and company details) transmitted over wireless networks must be protected by strong encryption
**Threat Analysis:** Analyzed how threat actors, such as cybercriminals or thrill-seekers, might attempt to intercept traffic on mobile access points
**Responsibility:** Maintained the mindset that security is an individual responsibility, ensuring the Pi was configured with secure credentials from the start[cite: 2].

### 💼 Professional Application (IT Support)
* **Linux Administration:** Proficiency in **Raspbian** shows I can manage Linux-based systems, which is common in server rooms and IoT environments.
* **Mobile Support:** This lab simulates supporting users in the field who rely on mobile hotspots for business connectivity.
* **Hardware Assembly:** Demonstrates the ability to troubleshoot physical display drivers and GPIO power issues, a key Tier 1 Help Desk skill.
  
---

# Lab #2: Conducting Vulnerability Scans using Nessus
**Objective:** To identify system weaknesses, analyze threat actor motivations, and understand the impact of potential data breaches.

Nessus Vulnerability Scan Dashboard
<img width="700" height="700" alt="Screenshot 2025-11-26 at 10 15 14 PM" src="https://github.com/user-attachments/assets/77e1c7b7-18a5-4d8e-8fd8-a0c5c3d17edb" />

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


<img width="1000" height="1000" alt="image" src="https://github.com/user-attachments/assets/77638c83-d2cc-49ea-b0d2-84685f19f838" />


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

