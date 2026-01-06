---
layout: default
title: Labs
---

# Coursework & Technical Labs

## Lab 1: Network Traffic Analysis (Wireshark)
**Objective:** Detected a simulated Man-in-the-Middle (MITM) attack on a local network.
* **Actions:** Captured packets using Wireshark; identified unencrypted HTTP POST data.
* **Results:** Successfully recovered "stolen" credentials and documented the vulnerability.
* **Mitigation:** Recommended enforcing TLS 1.3 and disabling LLMNR/NetBIOS.

---

**Objective:** To identify system weaknesses, analyze threat actor motivations, and understand the impact of potential data breaches.

![Nessus Vulnerability Scan Dashboard](./nessus-scan-screenshot.png)

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

![Active Directory Lab Screenshot] (<img width="612" height="792" alt="image" src="https://github.com/user-attachments/assets/77638c83-d2cc-49ea-b0d2-84685f19f838" />)


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
