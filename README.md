#  Hello, I'm Emir Raşit Gökçe

**SOC Analyst | SIEM Engineering | Threat Detection & Incident Response**

Welcome to my digital workspace! I am a Cyber Security professional based in Turkey, specializing in **Threat Detection, SIEM Engineering (Wazuh/Sysmon), and Blue Team Operations**. I build and actively operate personal SOC lab environments to simulate real-world attacks, engineer custom detection rules, and automate incident response workflows.

What sets me apart? I bridge the gap between technical defense and corporate risk. With a strong foundation in **IT Audit and GRC (ISO 27001/KVKK)**, I don't just hunt threats—I translate technical vulnerabilities into actionable business risks and compliance strategies.

---

## 🚀 Featured SOC & Detection Engineering Labs (Blue Team)

### 🔬 1. Enterprise SOC Lab: SMB Brute Force Detection & SIEM Rule Tuning
* **Concept:** Simulated a modern SMB brute-force attack using **CrackMapExec** and engineered custom detection logic within Wazuh to prevent alert fatigue.
* **Troubleshooting (RCA):** Identified and resolved critical SIEM evasion issues caused by broken XML syntax and duplicate Rule IDs in the backend analysis engine.
* **Detection Engineering:** Wrote a Level 12 critical correlation rule mapping `win.eventdata.targetUserName` to dynamically detect MITRE **T1110 (Brute Force)** attacks across the network.

### 🧠 2. Advanced SOC Architecture & Active Response Lab
* **Concept:** A comprehensive Purple Team environment designed to simulate and detect advanced persistent threats.
* **Detection & Integration:** Created custom XML decoders/rules for MITRE T1105 and integrated **Windows Defender Operational logs** directly into the SIEM for full endpoint visibility.
* **SOAR / Automation:** Engineered automated Active Response scripts to forcefully isolate malicious IPs via Windows Firewall instantly, drastically reducing MTTR.

### 🕵️‍♂️ 3. Live Memory Forensics & Credential Extraction (DFIR)
* **Concept:** An end-to-end Digital Forensics and Incident Response simulation focused on volatile memory analysis.
* **Action:** Bypassed OS-level driver restrictions to capture a live Physical Memory Dump (RAM) and utilized **Volatility 3** to map the execution chain (e.g., suspicious `cmd.exe` to `PING.EXE`).
* **Outcome:** Successfully extracted unencrypted, plaintext credentials directly from the process heap using advanced Linux string carving.

---

## ⚔️ Offensive Security & Vulnerability Research (Red Team)

### 🎯 Web Application Pentesting & Bug Bounty
* **Action:** Conducted ethical hacking and vulnerability research on global targets including T-Mobile, StoneX, Tesla, and Zomato.
* **Techniques:** Utilized Kali Linux, `ffuf`, `dig`, and manual API testing methodologies for OSINT and endpoint vulnerability analysis. 
* **Outcome:** Leveraged offensive insights to strengthen defensive monitoring capabilities and corporate risk reporting.

---

## 💼 GRC, IT Audit & Compliance (Risk Management)

### 📊 1. IT Audit & ISO 27001 Compliance Simulation (Ransomware)
* **Action:** Translated a dynamic WannaCry malware analysis into an executive IT Audit report. Mapped technical findings to **ISO 27001:2022** controls (A.8.8, A.5.15).
* **Outcome:** Simulated executive briefings, emphasizing *Risk Acceptance*, *Segregation of Duties (SoD)*, and *Least Privilege* architectures.

### ⚖️ 2. Incident Response & KVKK Compliance (Data Breach Crisis)
* **Action:** Orchestrated a simulated Incident Response protocol for a P2 Broken Access Control (BAC) vulnerability leading to PII exposure.
* **Outcome:** Executed the **KVKK 72-Hour Notification** regulatory requirement and drafted legally compliant public relations (PR) strategies.

---

## 🛠️ Arsenal & Technologies

* **Detection & SOC:** Wazuh SIEM, Sysmon, Windows Event Logs (4624, 4625, 4688, etc.), Custom XML Rule Tuning, Active Response.
* **DFIR & Blue Team:** Volatility 3, Memory Forensics, Incident Response Playbooks.
* **Offensive Security:** Kali Linux, CrackMapExec, Metasploit, Burp Suite, API Testing.
* **GRC & Auditing:** ISO 27001:2022, KVKK / GDPR Compliance, ITGC, Risk Assessment.

---

## 🏆 Certifications & Achievements
* **ISO 27001 Information Security Management System** - BTK Akademi
* **Introduction to Cybersecurity** - Cisco
* **TryHackMe:** Top 8% worldwide | Continuously sharpening vulnerability analysis skills.

---

## 📫 Let's Connect!
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/emir-raşit-gökçe-747bb439b/)
