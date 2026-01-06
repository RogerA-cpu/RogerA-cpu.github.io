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

## Lab 2: Vulnerability Assessment (Nessus/Nmap)
**Objective:** Scanned a "Metasploitable" virtual machine to identify critical security flaws.
* **Actions:** Ran intensive Nmap scans to find open ports; used Nessus for vulnerability scoring.
* **Results:** Identified an outdated version of VSFTPD vulnerable to a backdoor command execution.
* **Documentation:** [Link to PDF Report/Screenshot]

---

## Lab 3: Active Directory Lab
**Objective:** Set up a Windows Server 2022 environment to practice Group Policy management.
* **Actions:** Configured User OUs, implemented Password Complexity Policies, and restricted RDP access.
