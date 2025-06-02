# 🛡️ Cybersecurity Incident Response – Apex Financials  
### 🎓 Academic Project for BFOR 643 – Shalem Raju Maddirala

![GitHub Repo size](https://img.shields.io/github/repo-size/Shalem2020/apex-ir-bfor643-shalem?color=blue&style=flat-square)
![GitHub Last Commit](https://img.shields.io/github/last-commit/Shalem2020/apex-ir-bfor643-shalem?color=green&style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-Techniques%20Mapped-brightgreen?style=flat-square)
![Splunk](https://img.shields.io/badge/Splunk-Log%20Analysis%20Tool-orange?style=flat-square)

> 📁 **Type:** Course-based research project  
> 🧠 **Course:** BFOR 643 – Incident Handling  
> 🏫 **Institution:** University at Albany, SUNY  
> 👨‍💻 **Prepared by:** [Shalem Raju Maddirala](https://www.linkedin.com/in/shalemrajumaddirala)

---

## 📘 Project Summary

This repository presents a detailed investigation of two simulated cybersecurity incidents assigned as part of a university course. The analysis was performed using **Splunk**, focusing on log-based evidence and timeline reconstruction using real-world methods.

🎯 **Objectives:**
- Examine and break down two realistic cyberattacks
- Analyze and correlate logs to uncover attacker behavior
- Extract Indicators of Compromise (IoCs)
- Propose actionable security improvements
- Align findings with MITRE ATT&CK techniques

---

## 🔎 Incident Summaries

### 🪝 Incident 1 – Phishing Attack and Ransomware Deployment (INC250306)

- Attack initiated via spear-phishing email containing a macro-enabled PDF
- Host machine compromised through malicious macro execution
- Credentials stolen through pass-the-hash tactics
- Final payload encrypted internal systems with ShadowCrypt ransomware

**Mapped Tactics & Techniques:**  
`T1566.001`, `T1204.002`, `T1110`, `T1550.002`, `T1486`

---

### 🌐 Incident 2 – Public Web Server Breach and Data Leak (INC250422)

- Exploitation began with brute-force login and SQL injection on `/login.php`
- Remote access gained through uploaded web shells (`c99shell.php`, `eval-stdin.php`)
- Command execution and system enumeration observed in logs
- Over 50GB of internal data exfiltrated to a known attacker IP

**Mapped Tactics & Techniques:**  
`T1110`, `T1059.003`, `T1505.003`, `T1041`

---

## 🗂️ Files Included

| File | Description |
|------|-------------|
| `INC250306_5689_Group1_Report_Part1.pdf` | Technical report on phishing and ransomware incident |
| `INC40122_5689_Group_1_Report_Part2.pdf` | Analysis of web server compromise and data exfiltration |
| `Project_Part1_Resource_INC250306_5689.pdf` | Reference materials for first incident |
| `Project_Part2_Resource.pdf` | System/network layout for second incident |
| `Project_Presentation_Report2.pdf` | Final summary presentation with attack timeline |
| `Project_Part1_Logs.zip`, `Project_Part2_Logs.zip` | Log files examined using Splunk |
| `Project_Part2_Resource_INC250422.pptx` | Log screenshots and attack evidence (PowerPoint) |

---

## 🧰 Tools & Technologies Used

| Tool | Function |
|------|----------|
| ![Splunk](https://img.shields.io/badge/Splunk-Log%20Correlation-blue) | Parsing and querying logs for attack timeline |
| ![PDF](https://img.shields.io/badge/Adobe%20PDF-Reports-red) | Report generation and documentation |
| 🖥 Linux CLI | Manual file inspection, hash generation |
| 🧾 MITRE ATT&CK Framework | Threat behavior classification |

---

## 📚 Key Lessons Learned

- Multi-Factor Authentication (MFA) is critical to preventing unauthorized access  
- Input sanitization and PHP hardening help stop remote code execution  
- Log correlation and centralized monitoring drastically reduce response time  
- Endpoint detection must include script execution tracking  
- Clear response plans and secure coding reduce risk significantly

---

## 👨‍💼 Contributors

- Shalem Raju Maddirala (Author – [LinkedIn](https://www.linkedin.com/in/shalemrajumaddirala))  
- Leela Pavan Kumar K  
- Sriram R  
- SriVarsha A  
- Junaid M  
- Phanindhar Reddy K

---

## 📄 License

This work is released under:  
**Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International**  
🔗 [View Full License Terms](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

## 🌐 Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-shalem.me-black?style=for-the-badge)](https://shalem.me)  
[![GitHub](https://img.shields.io/badge/GitHub-Shalem2020-181717?logo=github&style=for-the-badge)](https://github.com/Shalem2020)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shalemrajumaddirala-blue?logo=linkedin&style=for-the-badge)](https://www.linkedin.com/in/shalemrajumaddirala)
