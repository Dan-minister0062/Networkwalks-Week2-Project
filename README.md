# 🔐 Networkwalks Week 2 – Penetration Testing Report
### Footprinting & Network Scanning Phases

<p align="center">
  <img src="https://img.shields.io/badge/Networkwalks-Cybersecurity%20Internship-blue?style=for-the-badge" alt="Networkwalks Internship"/>
  <img src="https://img.shields.io/badge/Batch-B082-success?style=for-the-badge" alt="Batch B082"/>
  <img src="https://img.shields.io/badge/Week-02-orange?style=for-the-badge" alt="Week 2"/>
  <img src="https://img.shields.io/badge/Platform-Kali%20Linux-purple?style=for-the-badge" alt="Kali Linux"/>
</p>

## 📌 Project Overview

This repository documents my **Week 2 practical cybersecurity project** as part of the Networkwalks Cybersecurity Internship (Batch B082).

The project focuses on two fundamental penetration-testing activities: **Footprinting and Network Scanning**. It demonstrates the practical application of reconnaissance tools in Kali Linux to gather publicly available domain information, identify network technologies, discover live hosts, and examine exposed network services within an authorized lab environment.

The project also documents the methodology, observations, technical findings, potential security risks, and recommendations derived from the exercises.

## 🎯 Project Objectives

- Understand the fundamentals of information gathering and footprinting.
- Perform domain reconnaissance using Kali Linux tools.
- Examine DNS records and domain-related information.
- Identify web technologies and inspect HTTP response headers.
- Understand Web Application Firewall (WAF) detection.
- Discover live hosts within an authorized local lab network.
- Identify open ports and running services using Zenmap/Nmap.
- Interpret scanning results and document potential security risks.
- Develop professional penetration-testing documentation.

## 📚 Modules Completed

| Module | Description | Status |
|---|---|---|
| W2-PM1 | Footprinting using multiple Kali Linux tools | ✅ Completed |
| W2-PM5 | Zenmap-based Network Scanning | ✅ Completed |
| W2-PM-FINAL | Final Penetration Testing Report | ✅ Completed |

## 🛠️ Tools and Technologies

The following tools were used during the practical exercises:

| Tool | Purpose |
|---|---|
| Kali Linux | Penetration-testing operating system |
| WHOIS | Domain registration and ownership information lookup |
| WhatWeb | Website technology and CMS fingerprinting |
| NSLookup | DNS queries and domain name resolution |
| cURL | HTTP requests and response-header inspection |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS information gathering and enumeration |
| Zenmap | Graphical interface for Nmap network scanning |
| Nmap | Network discovery, port scanning, and service identification |

## 🔎 Phase 1 – Footprinting and Information Gathering (W2-PM1)

**Objective:** Gather publicly available information about the authorized target domain, `networkwalks.com`, using multiple reconnaissance tools available in Kali Linux.

### Activities Performed

1. **WHOIS Lookup:** Examined publicly available domain registration information.
2. **WhatWeb:** Investigated website technologies and possible CMS information.
3. **NSLookup:** Queried DNS information and resolved domain names into IP addresses.
4. **cURL:** Inspected HTTP response headers and checked website connectivity.
5. **Wafw00f:** Investigated whether a Web Application Firewall was detected.
6. **DNSRecon:** Explored DNS-related information and records.

### Key Learning Outcomes

- Understood how public domain information can support reconnaissance.
- Learned how DNS resolution works.
- Practised identifying website technologies.
- Gained experience inspecting HTTP response headers.
- Understood the role of WAFs in protecting web applications.
- Developed familiarity with DNS enumeration techniques.

## 🌐 Phase 2 – Network Scanning (W2-PM5)

**Objective:** Discover active hosts and examine network services within the authorized local virtual lab environment using Zenmap and Nmap.

### Scanning Activities

| Scan Type | Purpose |
|---|---|
| Ping Scan | Discover active hosts without performing a port scan |
| Quick Scan | Quickly identify commonly exposed ports |
| Regular Scan | Perform a standard Nmap port scan |
| Intense Scan | Gather detailed information about ports, services, versions, and possible operating systems |
| Topology View | Visualize discovered hosts and their network relationships |

### Key Learning Outcomes

- Learned how to identify active devices within a network.
- Understood the relationship between IP addresses and network ranges.
- Identified open, closed, and filtered ports.
- Learned how to recognize running network services.
- Practised service-version detection.
- Understood how network topology visualization supports network analysis.

## 📸 Practical Screenshots and Evidence

The following screenshots document the practical exercises and demonstrate the commands and tools used throughout the project.

### 1. Footprinting – Information Gathering

**WHOIS – Domain Information**

![WHOIS Screenshot](https://github.com/user-attachments/assets/b77aeb0f-a22e-4fbd-953c-d820e1176af1)

**WHOIS – Additional Domain Lookup**

![WHOIS Additional Screenshot](https://github.com/user-attachments/assets/780227f3-9680-4a2a-acb1-ae4837411742)

**WhatWeb – Website Technology Fingerprinting**

![WhatWeb Screenshot](https://github.com/user-attachments/assets/316b21a9-def4-4fed-9836-40a75075acaf)

**NSLookup – DNS Resolution**

![NSLookup Screenshot](https://github.com/user-attachments/assets/4aa43863-a48b-4af2-9d95-424e368919d7)

**NSLookup – Additional DNS Testing**

![NSLookup Additional Screenshot](https://github.com/user-attachments/assets/02d17a4b-5d37-436b-9e23-51fe45776748)

**cURL – HTTP Response Header Inspection**

![cURL Screenshot](https://github.com/user-attachments/assets/5df9f1d9-a664-4190-a2e2-7dff9bb49a87)

**Wafw00f – WAF Detection**

![Wafw00f Screenshot](https://github.com/user-attachments/assets/99a02984-4b91-4b7b-8880-91a761da244b)

**DNSRecon – DNS Enumeration**

![DNSRecon Screenshot](https://github.com/user-attachments/assets/cdcae87d-d658-4696-9b4b-1a41c258eb81)

### 2. Zenmap – Network Scanning

**01 – Ping Scan: Host Discovery**

![Zenmap Ping Scan](https://github.com/user-attachments/assets/c8cb5857-484a-4ac8-81b4-8e20242878c6)

**02 – Intense Scan: Port and Service Detection**

![Zenmap Intense Scan](https://github.com/user-attachments/assets/0e39de87-6591-4485-926a-26c4dca7c832)

**03 – Network Topology Visualization**

![Zenmap Topology](https://github.com/user-attachments/assets/a5d0a8d9-5104-4df2-841b-775e1fe7f32e)

**04 – Regular Scan: Network and Port Analysis**

![Zenmap Regular Scan](https://github.com/user-attachments/assets/f6e0c857-3dd1-4cdd-a141-c6cde7d5a5cf)

## 📄 Final Penetration Testing Report

The complete report provides a more detailed explanation of the practical exercises, including:

- Project introduction and scope.
- Testing methodology and procedures.
- Tools and commands used.
- Practical observations and findings.
- Network scanning results.
- Potential security risks.
- Security recommendations.
- Conclusion and lessons learned.

📥 **[View / Download the Complete Week 2 Report (PDF)](./Week2_Report.pdf)**

## 🛡️ Security, Scope and Ethical Considerations

All activities were conducted for educational and cybersecurity training purposes, within the authorized scope defined by the internship.

- Reconnaissance activities were limited to the approved project scope.
- Network scanning was intended for the authorized local lab environment.
- No exploitation or disruptive testing was performed.
- No unauthorized access to systems or sensitive information was attempted.

This project demonstrates the importance of responsible information gathering, network assessment, and ethical cybersecurity practices.

## 💡 Skills Developed

Through this project, I strengthened my practical understanding of:

- Footprinting and reconnaissance.
- DNS analysis and domain resolution.
- Web technology fingerprinting.
- HTTP response inspection.
- WAF detection.
- DNS enumeration.
- Network host discovery.
- Port and service scanning.
- Service-version identification.
- Network topology analysis.
- Technical reporting and documentation.
- Ethical penetration-testing practices.

## 🚀 Conclusion

Completing Week 2 of the Networkwalks Cybersecurity Internship provided valuable hands-on experience with information gathering and network scanning.

By combining multiple Kali Linux reconnaissance tools with Zenmap/Nmap, I gained a better understanding of how security professionals collect information, identify exposed network services, analyze infrastructure, and document potential security concerns.

This project represents another step in my continuous journey toward developing practical cybersecurity skills and building a professional cybersecurity portfolio.

---

<p align="center">
  <b>🔐 Learn • Practise • Analyze • Secure</b>
  <br/>
  <i>Building practical cybersecurity knowledge, one project at a time.</i>
</p>
