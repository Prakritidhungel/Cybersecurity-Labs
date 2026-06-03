# 🛡️ Cybersecurity Labs Portfolio

**Prakriti Dhungel** | M.S. Cybersecurity — University of North Texas  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/prakritidhungel)
[![Email](https://img.shields.io/badge/Email-prakriti.dhungel98%40gmail.com-D14836?style=flat&logo=gmail)](mailto:prakriti.dhungel98@gmail.com)
![Labs](https://img.shields.io/badge/Labs%20Completed-30%2B-brightgreen?style=flat)
![Status](https://img.shields.io/badge/Status-Graduate-blue?style=flat)

---

## 📌 About This Repository

This repository showcases hands-on cybersecurity lab work completed during my M.S. in Cybersecurity at the **University of North Texas** (GPA: 3.9). The labs span network security, web application security, digital forensics, vulnerability assessment, and AI security — covering both offensive techniques and defensive countermeasures in controlled, ethical environments.

> All labs were conducted in isolated virtual machine environments using industry-standard tools and frameworks (SEED Labs, Kali Linux, Nessus, Wireshark, Azure, and more).

---

## 📂 Lab Categories

| # | Category | Labs Included |
|---|----------|--------------|
| 1 | [🌐 Network Security](#-network-security) | Network Scanning, Packet Sniffing, Wireshark Analysis (HTTP, NAT, UDP, Ethernet/ARP) |
| 2 | [🔐 Cryptography & Authentication](#-cryptography--authentication) | Cryptography (OpenSSL), Password Cracking (JtR), SSH Key Authentication |
| 3 | [💉 Web Application Security](#-web-application-security) | SQL Injection, XSS, CSRF, Buffer Overflow, Race Condition, Full-Stack Setup |
| 4 | [🧱 Vulnerability Assessment](#-vulnerability-assessment) | Nessus Scanning (Internal Network, Linux-specific), WAF Testing (Azure) |
| 5 | [🔬 Digital Forensics](#-digital-forensics) | Windows/Linux/Mobile/Network/Memory Forensics, Steganography, File Recovery, Incident Response |
| 6 | [🛡️ Threat Detection & Mitigation](#️-threat-detection--mitigation) | Ransomware Detection/Monitoring Script, Host-Based Ransomware Mitigation |
| 7 | [🤖 AI Security & Systems](#-ai-security--systems) | CAN Bus ML Analysis, AI Architecture Assessment |

---

## 🌐 Network Security

### Lab 1a — Network Scanning
**Course:** CSCE 5550 | **Tool:** Kali Linux, nmap  
**Overview:** Introduced active reconnaissance techniques using Kali Linux. Performed host discovery and service enumeration using nmap, collecting intelligence on IP addresses, operating systems, open ports, and running services.  
**Skills Demonstrated:** Network enumeration, OS fingerprinting, service discovery, scan type differentiation (TCP SYN, UDP, version detection)

---

### Lab 1b — Packet Sniffing with Wireshark
**Course:** CSCE 5550 | **Tool:** Kali Linux, Wireshark  
**Overview:** Captured and analyzed live network traffic using Wireshark on a Kali Linux VM. Inspected packet-level data at the protocol layer to understand how unencrypted data traverses a network.  
**Skills Demonstrated:** Traffic capture, protocol inspection, interface configuration, live packet filtering

---

### CSCE 5585 Lab 2 — Wireshark HTTP Traffic Analysis
**Course:** CSCE 5585 | **Tool:** Wireshark  
**Overview:** Analyzed HTTP GET/response interactions at the packet level. Examined HTTP message structures, HTTP authentication mechanisms, and basic web security behaviors. Explored multi-object page loads and response behavior across connection types.  
**Skills Demonstrated:** HTTP protocol analysis, authentication header inspection, request/response cycle understanding

---

### CSCE 5585 Lab 3 — In-Depth Packet Analysis and Protocol Exploration
**Course:** CSCE 5585 | **Tool:** Wireshark  
**Overview:** Performed deep protocol analysis with a focus on UDP transport behavior. Used nslookup to generate DNS queries and analyzed the resulting UDP packets, examining header fields (source/destination ports, checksum, payload length), protocol numbers, and packet structure.  
**Skills Demonstrated:** UDP analysis, DNS traffic inspection, protocol header interpretation, Wireshark filtering

---

### CSCE 5585 Lab 4 — Advanced Wireshark: NAT and Protocol Analysis
**Course:** CSCE 5585 | **Tool:** Wireshark, pcap trace files  
**Overview:** Analyzed NAT (Network Address Translation) behavior by comparing packet captures from both the home-side and ISP-side of a simulated network. Examined IP address translation, TCP header changes, and stream behavior across NAT boundaries.  
**Skills Demonstrated:** NAT analysis, TCP stream filtering, IP address translation, dual-trace comparison

---

### CSCE 5585 Lab 5 — Ethernet Frames and ARP Analysis
**Course:** CSCE 5585 | **Tool:** Wireshark  
**Overview:** Captured and dissected Ethernet frames and ARP (Address Resolution Protocol) packets. Analyzed MAC address structure, protocol encapsulation, manufacturer lookup, and ARP response timing in a live environment.  
**Skills Demonstrated:** Layer 2 analysis, ARP protocol behavior, Ethernet frame structure, MAC address identification

---

## 🔐 Cryptography & Authentication

### Lab 3a — Cryptography with OpenSSL
**Course:** CSCE 5550 | **Tool:** OpenSSL, Ubuntu VM  
**Overview:** Applied core cryptographic primitives hands-on using OpenSSL. Implemented symmetric encryption, public-key encryption, digital signatures, public-key certificates, and SSH key-based authentication. Gained practical understanding of the TLS/SSL cryptographic toolkit.  
**Skills Demonstrated:** Symmetric/asymmetric encryption, digital signatures, PKI fundamentals, SSH authentication, OpenSSL CLI

---

### Lab 3b — Password Cracking with John the Ripper
**Course:** CSCE 5550 | **Tool:** John the Ripper, Ubuntu VM  
**Overview:** Performed offline password attacks using both brute-force and dictionary attack methods with John the Ripper. Analyzed password hash formats and explored how weak password policies create exploitable vulnerabilities.  
**Skills Demonstrated:** Offline password attacks, hash cracking, dictionary/brute-force methodology, password security analysis

---

### Bonus Homework — Passwordless SSH with Public/Private Key Authentication
**Course:** CSCE 5550 | **Tool:** ssh-keygen, Ubuntu VM  
**Overview:** Configured passwordless SSH authentication by generating RSA key pairs using `ssh-keygen`, distributing the public key via `authorized_keys`, and validating key-based login. Documented each configuration step with annotated screenshots.  
**Skills Demonstrated:** SSH key management, `ssh-keygen`, public/private key configuration, secure remote access

---

## 💉 Web Application Security

### Lab 1 — Full-Stack Web Development Environment Setup (Kali Linux)
**Course:** CSCE 4560/5560 | **Tool:** Apache, MariaDB, PHP, WordPress, Kali Linux 2025.4  
**Overview:** Configured a complete full-stack LAMP web environment on Kali Linux as a foundation for secure web application testing. Set up Apache web server, MySQL/MariaDB database, PHP runtime, and WordPress CMS. Established a baseline secure configuration for subsequent security labs.  
**Skills Demonstrated:** Linux server administration, LAMP stack setup, WordPress configuration, VM environment management

---

### Lab 2 — Information Gathering and WebGoat Attacks
**Course:** CSCE 4560/5560 | **Tool:** OWASP WebGoat, Kali Linux  
**Overview:** Used OWASP WebGoat, a deliberately vulnerable web application, to identify and exploit common web vulnerabilities in a legal, sandboxed environment. Covered SQL injection, XSS, CSRF, insecure deserialization, and Buffer Overflow attacks — along with secure coding countermeasures.  
**Skills Demonstrated:** OWASP Top 10 exploitation, WebGoat navigation, vulnerability identification, security best practices

---

### Lab 2 (CSCE 5550) — Cross-Site Scripting (XSS) Attack — SEED Lab
**Course:** CSCE 5550 | **Tool:** SEED Lab, SEEDUbuntu VM  
**Overview:** Conducted a multi-task XSS attack simulation using the SEED Lab platform. Tasks included injecting malicious scripts to trigger alert windows, harvesting session cookies, stealing victim cookies via a netcat listener, and forging friend requests by hijacking authenticated sessions (CSRF-adjacent technique).  
**Skills Demonstrated:** Reflected/stored XSS, cookie theft, session hijacking, JavaScript injection, netcat listener setup

---

### Lab 5 — Cross-Site Request Forgery (CSRF) Attack — SEED Lab
**Course:** CSCE 5550 | **Tool:** SEED Lab, SEEDUbuntu-16.04 VM, Elgg social network app  
**Overview:** Exploited CSRF vulnerabilities in the Elgg social networking application. Demonstrated how a forged HTTP request from a malicious site can execute unauthorized actions (profile updates, friend additions) on behalf of an authenticated victim without their knowledge.  
**Skills Demonstrated:** CSRF attack construction, HTTP request forging, same-origin policy analysis, CSRF token bypass concepts

---

### Lab 6 — SQL Injection Attack — SEED Lab
**Course:** CSCE 5550 | **Tool:** SEED Lab, SEEDUbuntu-16.04 VM  
**Overview:** Exploited SQL injection vulnerabilities in a purpose-built vulnerable web application. Demonstrated authentication bypass, data extraction, and database manipulation through maliciously crafted SQL queries. Reinforced understanding of parameterized queries as a mitigation.  
**Skills Demonstrated:** SQL injection (in-band), authentication bypass, database enumeration, prepared statement defense

---

### Assignment 2 (CYB 5552) — Buffer Overflow Attack
**Course:** CYB 5552 | **Tool:** Custom VM, C exploitation  
**Overview:** Conducted a buffer overflow attack against a vulnerable C program (`getscore`). Analyzed memory layout, identified the overflow boundary, and crafted a payload to overwrite the return address and escalate to root privileges. Documented the complete exploit chain with annotated screenshots.  
**Skills Demonstrated:** Stack-based buffer overflow, memory analysis, privilege escalation, exploit development fundamentals

---

### Race Condition Vulnerability Lab — SEED Lab
**Course:** CSCE 5550 | **Tool:** SEED Lab, Ubuntu VM  
**Overview:** Exploited a race condition vulnerability in a privileged program using parallel process execution. Leveraged symlink manipulation to "race" the privileged program and gain root access. Also evaluated sticky symlink protection and principle of least privilege as countermeasures.  
**Skills Demonstrated:** Race condition exploitation, symlink attacks, TOCTOU vulnerabilities, privilege escalation, least privilege principle

---

## 🧱 Vulnerability Assessment

### Lab 3 — Nessus Vulnerability Scanning
**Course:** CSCE 4560/5560 | **Tool:** Tenable Nessus, Kali Linux, Metasploitable 2  
**Overview:** Installed, configured, and executed a Nessus vulnerability scan against a Metasploitable 2 target. Identified and classified vulnerabilities by severity (Critical/High/Medium/Low), interpreted Nessus findings, and documented remediation strategies.  
**Skills Demonstrated:** Vulnerability scanning, Nessus configuration, CVE identification, risk classification, remediation planning

---

### Nessus Scan Reports — Internal Network & Linux-Specific Assessments
**Tool:** Tenable Nessus  
**Overview:** Generated and analyzed two Tenable Nessus scan reports: an internal network scan targeting `192.168.1.2` across all vulnerability categories, and a Linux-specific assessment of the same host. Reports include host-level vulnerability breakdowns by severity, enabling targeted hardening decisions.  
**Skills Demonstrated:** Nessus report interpretation, host-based vulnerability profiling, Linux security posture assessment, remediation prioritization

---

### WAF Lab — Azure Web Application Firewall Security Testing
**Course:** CSCE 5214 / CSCE 4560/5560 | **Tool:** Azure Application Gateway, Azure WAF (OWASP CRS 3.2), Azure Log Analytics  
**Overview:** Deployed and tested an Azure Web Application Firewall in Prevention mode protecting a Python 3.11 web application hosted on Azure App Service. Simulated OWASP Top 10 attacks (XSS, SQL Injection, Path Traversal, automated scanner reconnaissance) using `curl` from both local macOS and Azure Cloud Shell. Retrieved and analyzed real WAF firewall logs from Azure Log Analytics (`AGWFirewallLogs`), confirming rule triggers including Rule 941150 (XSS Filter), Rule 941160 (NoScript XSS), and Rule 949110 (Anomaly Score Exceeded).  
**Skills Demonstrated:** Cloud WAF configuration, OWASP CRS rule analysis, attack simulation, Azure Log Analytics querying, security log interpretation

---

## 🔬 Digital Forensics

> Labs completed using the *Digital Forensics, Investigation, and Response (4th Edition)* platform.

### Lab 02 — Recognizing Steganography in Forensic Evidence
**Time on Task:** 9 hrs 38 min | **Progress:** 100%  
**Overview:** Analyzed digital media for hidden data embedded via steganographic techniques. Applied forensic tools to detect concealed information within image and audio files, and documented findings following forensic best practices.  
**Skills Demonstrated:** Steganography detection, digital media forensics, evidence documentation

---

### Lab 03 — Recovering Deleted and Damaged Files
**Time on Task:** 11 hrs 4 min | **Progress:** 100%  
**Overview:** Applied file carving and forensic recovery methods to retrieve deleted and damaged files from disk images. Examined file system structures to locate recoverable data and document recovery methodology.  
**Skills Demonstrated:** File carving, disk image analysis, file system structure, forensic recovery tools

---

### Lab 04 — Conducting an Incident Response Investigation
**Time on Task:** 6 hrs 54 min | **Progress:** 100%  
**Overview:** Executed a structured incident response workflow across detection, containment, eradication, and recovery phases. Analyzed forensic artifacts to reconstruct an attack timeline and compile a findings report.  
**Skills Demonstrated:** Incident response lifecycle, forensic artifact analysis, timeline reconstruction, IR reporting

---

### Lab 05 — Forensic Investigations on Windows Systems
**Time on Task:** 4 hrs 34 min | **Progress:** 100%  
**Overview:** Investigated a Windows system for forensic evidence. Examined registry hives, event logs, prefetch files, and user activity artifacts to reconstruct attacker actions and document findings.  
**Skills Demonstrated:** Windows forensic artifacts, registry analysis, event log review, Windows file system investigation

---

### Lab 06 — Forensic Investigations on Linux Systems
**Time on Task:** 4 hrs 42 min | **Progress:** 100%  
**Overview:** Conducted forensic analysis of a Linux system, examining log files, bash history, hidden directories, cron jobs, and user account artifacts. Applied forensically sound methods to preserve and document evidence.  
**Skills Demonstrated:** Linux forensic artifacts, log analysis, filesystem investigation, chain of custody

---

### Lab 08 — Forensic Investigations on Mobile Devices
**Time on Task:** 8 hrs 54 min | **Progress:** 100%  
**Overview:** Performed a mobile device forensic investigation, acquiring and analyzing data from a mobile platform. Examined call logs, SMS records, app data, and geolocation artifacts.  
**Skills Demonstrated:** Mobile forensics, data acquisition, app artifact analysis, mobile evidence handling

---

### Lab 09 — Forensic Investigations on Network Infrastructure
**Time on Task:** 2 hrs 24 min | **Progress:** 100%  
**Overview:** Analyzed network forensic evidence including packet captures, router logs, and firewall records to identify malicious activity and trace attacker movement across infrastructure.  
**Skills Demonstrated:** Network forensics, PCAP analysis, log correlation, intrusion tracing

---

### Lab 10 — Forensic Investigations on System Memory
**Time on Task:** 5 hrs 44 min | **Progress:** 100%  
**Overview:** Conducted volatile memory forensics on a running system image. Extracted and analyzed process lists, network connections, loaded modules, and artifacts resident only in RAM to detect malicious activity.  
**Skills Demonstrated:** Memory forensics, RAM artifact analysis, process analysis, malware detection in memory

---

### Web SQL Injection — Forensic Variant (SEED Lab)
**Tool:** SEED Lab, SEEDUbuntu VM  
**Overview:** Explored SQL injection from a forensic angle, examining how attacks are executed, what database artifacts they leave, and how defenders can detect and document injection attempts through log analysis.  
**Skills Demonstrated:** SQL injection forensics, database log analysis, attack documentation, defensive detection

---

## 🛡️ Threat Detection & Mitigation

### Ransomware Monitoring Script
**Tool:** Python  
**Overview:** Developed a Python-based ransomware monitoring tool that watches a user-specified directory for behavioral indicators of ransomware activity — including rapid file modifications, suspicious file extension renames (e.g., `.locked`), and matching of running process names against a curated threat list. Alerts are triggered in real time without relying on third-party antivirus software.  
**Key Functions:**
- **Process Monitoring:** Detects running processes matching known ransomware signatures
- **File System Monitoring:** Tracks rapid file creations, modifications, and renames
- **Extension Heuristics:** Flags suspicious encrypted-file extensions  
**Skills Demonstrated:** Python scripting, filesystem event monitoring, behavioral detection, ransomware indicators of compromise (IoCs)

---

### Host-Based Ransomware Detection and Mitigation (Without Third-Party Tools)
**Overview:** Documented a host-based ransomware detection and mitigation strategy relying entirely on built-in OS tools — no commercial antivirus required. Covered malicious process termination (`taskkill`, `kill -9`), real-time file monitoring (`inotifywait`, PowerShell), permission hardening (`chmod`, `icacls`), event log monitoring (Windows Event ID 4688, Linux syslog), and outbound firewall rule configuration.  
**Skills Demonstrated:** Host hardening, process monitoring, permission management, native OS security tooling, defense-in-depth

---

## 🤖 AI Security & Systems

### CSCE 5214 — Assignment 4: CAN Bus ML Architecture Assessment
**Course:** CSCE 5214 | **Tool:** Python, Random Forest, CAN bus simulator  
**Overview:** Assessed the architecture of a real-time AI system designed to detect CAN bus attacks in automotive networks. Analyzed the performance gap between a CAN data simulator (generating batches every ~1 second) and a Random Forest classifier (processing time of 8–9 seconds per batch). Evaluated data loss implications for vehicle cybersecurity, and recommended lightweight model alternatives for time-sensitive deployments.  
**Key Findings:** Processing time was 8–9× slower than data generation rate; the system relied on queuing to handle backlog, but latency in attack detection could be critical in real vehicle environments.  
**Skills Demonstrated:** AI system architecture analysis, real-time ML trade-offs, CAN bus security, model performance evaluation, cybersecurity implications of AI

---

## 🧰 Tools & Technologies

| Domain | Tools |
|--------|-------|
| **Network Analysis** | Wireshark, nmap, netcat, tcpdump |
| **Vulnerability Scanning** | Tenable Nessus, OWASP ZAP |
| **Web Security** | SEED Labs, WebGoat, Burp Suite, curl |
| **Cryptography** | OpenSSL, John the Ripper, ssh-keygen |
| **Cloud Security** | Azure Application Gateway, Azure WAF, Azure Log Analytics |
| **Digital Forensics** | Autopsy, Volatility, forensic VM platforms |
| **Programming** | Python, Bash, C |
| **Operating Systems** | Kali Linux, Ubuntu, Windows Server |
| **Virtualization** | VirtualBox, OVA-based VM environments |

---

## 📚 Courses Represented

| Course | Title |
|--------|-------|
| CSCE 5550 | Computer Security |
| CSCE 4560 / 5560 | Secure Electronic Commerce |
| CSCE 5585 | Network Security |
| CSCE 5214 | AI / Software Development |
| CYB 5552 | Applied Cybersecurity |

---

## ⚠️ Ethical Notice

All labs in this repository were conducted in **isolated, controlled virtual machine environments** for **academic purposes only**. No real systems, networks, or individuals were targeted. Techniques demonstrated here are for educational understanding of offensive methods and how to defend against them.

---

*Prakriti Dhungel — M.S. Cybersecurity, University of North Texas (May 2026)*  
*Specialization: Identity & Access Management (IAM) | SOC Analysis | Cloud Security*
