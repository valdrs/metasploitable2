#  Metasploitable2 Penetration Test | Offensive Security Project

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Scope](https://img.shields.io/badge/Assessment-Lab_Environment-blue)
![Category](https://img.shields.io/badge/Focus-Offensive_Security-red)
![Report](https://img.shields.io/badge/Output-Professional_Report-black)

This repository contains a structured penetration test performed against the intentionally vulnerable **Metasploitable2** machine.  
The assessment simulates a real-world offensive security engagement, covering reconnaissance, enumeration, exploitation, documentation, and reporting.

> ⚠️ **Legal Disclaimer:**  
> All testing was performed in an authorized lab environment. Do **not** use these techniques on systems you do not own or have permission to test.

---

## 📍 Project Summary

| Attribute | Details |
|----------|---------|
| **Target** | Metasploitable2 VM |
| **Assessment Type** | Host-level penetration test |
| **Testing Style** | Black-box with staged escalation |
| **Objective** | Identify vulnerabilities, validate exploitability, and produce a security report |
| **Evaluator** | **Valdrs** |

---

## 🧭 Methodology

This engagement followed a structured penetration testing lifecycle:

Reconnaissance → Enumeration → Vulnerability Mapping → Exploitation → Documentation



### Tools Used

| Category | Tools |
|----------|-------|
| Recon & Scanning | `nmap`, `gobuster` |
| Enumeration & Validation | `smbclient`, `ftp`, browser-based testing |
| Exploitation | `Metasploit Framework`, `sqlmap` |
| Documentation | Google Docs, screenshots, structured reporting |

---

## 🔍 Key Findings

| ID | Vulnerability | Severity | Exploited |
|----|--------------|----------|-----------|
| F-03 | vsftpd 2.3.4 Backdoor RCE | **Critical** | ✅ |
| F-05 | SQL Injection in DVWA | High | ✅ |
| F-06 & F-07 | Reflected + Stored XSS | High | ✅ |
| F-02 | Exposed administrative panels | High | ⚠️ Observed |
| F-04 | SMB Information Disclosure | Medium | ⚠️ Observed |

📁 Full details available in the `/docs/` report.

---

## 📄 Documentation & Evidence

| Folder | Contents |
|--------|----------|
| `/docs/` | Full formatted penetration test report (Google Docs ready) |
| `/evidence/` | Screenshots: scans, exploits, payloads, PoC validation |


Example screenshots include:

- `nmap_scan.png`
- `sqlmap_dump.png`
- `vsftpd_shell.png`
- `xss_payload.png`

---

## 🧠 Skills Demonstrated

- Penetration testing methodology
- Vulnerability exploitation and validation
- Report writing for both technical and executive audiences
- Use of offensive tooling (Metasploit, sqlmap, Gobuster)
- Interpreting service misconfigurations and insecure deployments
- Evidence-based documentation and ethical testing discipline

---

## 📌 Learning Outcomes

This engagement reinforced:

- Systematic vulnerability analysis
- Hands-on exploitation workflow
- Practical application of OWASP & PTES methodologies
- Clear technical reporting and documentation

---

## 🏷️ Tags

`Cybersecurity` `Penetration-Testing` `Red-Team` `Metasploit`  
`sqlmap` `XSS` `SQLi` `Enum` `Network-Security`  
`OWASP` `Linux` `Ethical-Hacking` `Metasploitable2`

---
