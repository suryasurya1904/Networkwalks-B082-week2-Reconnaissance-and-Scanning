# Networkwalks-B082-week2-Reconnaissance-and-Scanning
Networkwalks-B082-Week2

Cybersecurity & Ethical Hacking — Week 2

This repository contains my Week 2 Cybersecurity & Ethical Hacking project work, covering footprinting, reconnaissance, information gathering, and network scanning using Kali Linux tools and Zenmap.

📁 Project Modules

W2-PM1 — Footprinting & Reconnaissance with Multiple Kali Tools

This module covers passive reconnaissance using:

- "whois" — Domain registration information
- "whatweb" — Web technology fingerprinting
- "nslookup" — DNS/IP resolution
- "curl -I" — HTTP response headers
- "wafw00f" — WAF detection
- "dnsrecon" — DNS record enumeration

The objective is to understand how publicly available information can be collected during the reconnaissance phase.

---

W2-PM4 — Footprinting & Reconnaissance with theHarvester

This module focuses on gathering publicly available information using theHarvester.

Tasks include:

- Finding email IDs and sub-domains
- Searching public sources
- Using Baidu as a data source
- Using multiple/all available sources
- Saving screenshots and command outputs

Example commands used in the lab:

theHarvester -d microsoft.com -l 1000 -b baidu

theHarvester -d microsoft.com -l 50 -b all

TheHarvester gathers information such as emails, sub-domains, and hosts from public sources.

---

W2-PM5 — Network Scanning with Zenmap

This module introduces Zenmap, the official GUI version of Nmap.

Tasks include:

1. Installing Zenmap
2. Finding the local IP address and LAN subnet
3. Finding live hosts
4. Counting live hosts
5. Identifying live-host IP addresses
6. Identifying MAC addresses
7. Saving the network topology as a PDF

Zenmap provides a beginner-friendly graphical interface for Nmap and supports reusable scan profiles.

---

🛠️ Tools & Technologies

Tool| Purpose
Kali Linux| Cybersecurity testing environment
WHOIS| Domain information
WhatWeb| Technology fingerprinting
Nslookup| DNS resolution
cURL| HTTP header analysis
Wafw00f| WAF detection
DNSRecon| DNS enumeration
theHarvester| Public information gathering
Zenmap| Network scanning and visualization
Nmap| Network discovery and security scanning

📂 Repository Structure

Networkwalks-B082-week2/
│
├── WK-2-PM1/
│   └── Footprinting & Reconnaissance
│
├── WK2-PM4/
│   └── Footprinting with theHarvester
│
├── WK2-PM5/
│   └── Network Scanning with Zenmap
│
├── WK2-PM-FINAL-REPORT/
│   └── Week 2 Final Report
│
└── README.md

🎯 Learning Objectives

By completing these projects, I learned the fundamentals of:

- Footprinting and reconnaissance
- Passive information gathering
- DNS enumeration
- Web technology fingerprinting
- HTTP header analysis
- WAF identification
- Email and sub-domain discovery
- Network host discovery
- Network scanning with Zenmap/Nmap
- Recording and documenting cybersecurity lab results

⚠️ Ethical Use

All activities in this repository are intended for educational and authorized cybersecurity training purposes only.

Security tools should only be used against systems that you own, your own lab environment, or systems for which you have explicit permission to test. The training material also emphasizes that unauthorized access is illegal.

📚 Week 2 Summary

Week 2 focuses on understanding how security professionals gather information about systems before performing security testing.

The workflow covered in these projects is:

Reconnaissance
      ↓
Information Gathering
      ↓
Technology Fingerprinting
      ↓
DNS Enumeration
      ↓
Network Discovery
      ↓
Network Scanning
      ↓
Documentation & Reporting

---

👨‍💻 Author

Surya R

Cybersecurity & Ethical Hacking — Week 2 Project

---

⭐ Learning cybersecurity responsibly, one project at a time.

