# 🛡️ CyberOps Academy — Day 6: Security Frameworks & Standards

![Phase](https://img.shields.io/badge/Phase-1%20Foundations-blue) ![Day](https://img.shields.io/badge/Day-6%20of%2030-orange) ![XP](https://img.shields.io/badge/XP-100-green) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **CyberOps Academy 30-Day Analyst Bootcamp** | Offline Edition  
> 📅 Completed: April 15, 2026

---

## 📊 Day 6 Overview

| Field | Details |
|---|---|
| **Topic** | Security Frameworks & Standards |
| **Phase** | Phase 1 — Foundations |
| **XP Reward** | 100 XP |
| **Key Frameworks** | NIST CSF, MITRE ATT&CK, CIS Controls, ISO 27001 |
| **Date Completed** | April 15, 2026 |

---

## 📌 Why Frameworks Matter

Frameworks provide a **structured approach** to cybersecurity. Without them, organizations would have no consistent way to measure, improve, or communicate their security posture.

- Every job interview will ask about these
- They form the backbone of compliance, auditing, and SOC operations
- Security teams align their tools and workflows to framework functions

---

## 🏗️ NIST Cybersecurity Framework (CSF)

The **most widely adopted** cybersecurity framework globally. Built around 5 core functions — remember the acronym **IPDRR**:

| Function | Description |
|---|---|
| **Identify** | Know your assets, risks, and environment |
| **Protect** | Implement safeguards (access control, training, encryption) |
| **Detect** | Monitor for anomalies and events (SIEM, IDS) |
| **Respond** | Take action on detected incidents (IR plans) |
| **Recover** | Restore services and learn from incidents |

### Key Points:
- Developed by NIST (National Institute of Standards and Technology)
- Voluntary but widely adopted across industries
- NIST CSF 2.0 added a 6th function: **Govern**
- Maps directly to many compliance requirements (HIPAA, PCI-DSS, etc.)

---

## 🎯 MITRE ATT&CK Framework — Your Most Important Tool

ATT&CK is a **knowledge base of adversary tactics and techniques** based on real-world observations. It maps out exactly how attackers operate from initial access to exfiltration.

### Structure:

| Component | Description |
|---|---|
| **Tactics** | The "why" — attacker's goal (e.g., Lateral Movement, Exfiltration) |
| **Techniques** | The "how" — specific method used (e.g., T1059 = Command Line Interface) |
| **Sub-techniques** | More granular breakdown of techniques |
| **Mitigations** | Recommended defensive actions |
| **Detections** | How to detect the technique |

### ATT&CK Tactics (Enterprise):
1. Reconnaissance
2. Resource Development
3. Initial Access
4. Execution
5. Persistence
6. Privilege Escalation
7. Defense Evasion
8. Credential Access
9. Discovery
10. Lateral Movement
11. Collection
12. Command and Control
13. Exfiltration
14. Impact

### Why It Matters:
- Every SOC analyst references ATT&CK daily
- Used for threat hunting, detection engineering, and incident response
- Helps map alerts to real attacker behavior
- Free resource at: https://attack.mitre.org

---

## 📋 CIS Controls — 18 Prioritized Security Actions

The **Center for Internet Security (CIS)** provides 18 controls in 3 implementation groups. Start with **IG1** for basic cyber hygiene:

### Implementation Groups:

| Group | Target | Description |
|---|---|---|
| **IG1** | Small orgs / limited IT | Basic cyber hygiene — essential controls |
| **IG2** | Medium orgs | Additional controls for managing sensitive data |
| **IG3** | Large orgs / mature security | Advanced controls for high-risk environments |

### Key CIS Controls (Analyst Focus):

| Control # | Control Name | Why It Matters |
|---|---|---|
| 1 | Inventory of Enterprise Assets | Can't protect what you don't know about |
| 2 | Inventory of Software Assets | Unauthorized software = attack surface |
| 5 | Account Management | Manage credentials and access |
| 6 | Access Control Management | Least privilege principle |
| 8 | Audit Log Management | **Analysts live here** — logs are evidence |
| 10 | Malware Defenses | AV, EDR, sandboxing |
| 13 | Network Monitoring and Defense | IDS/IPS, traffic analysis |
| 17 | Incident Response Management | IR plan and playbooks |

---

## 📜 ISO/IEC 27001 — International Security Standard

ISO 27001 is the international standard for **Information Security Management Systems (ISMS)**.

### Key Facts:
- Provides a risk-based approach to information security
- Organizations can get **certified** by auditors
- Covers 93 controls organized in 4 themes (ISO 27001:2022)
- Domains include: Organizational, People, Physical, Technological
- Widely required for enterprise vendor contracts and compliance

### ISMS Core Cycle (Plan-Do-Check-Act):
```
PLAN  → Define scope, risk assessment, policies
DO    → Implement controls and procedures
CHECK → Monitor, audit, measure effectiveness
ACT   → Improve based on findings
```

---

## 🔄 Framework Comparison

| Framework | Origin | Type | Best Used For |
|---|---|---|---|
| NIST CSF | USA (NIST) | Voluntary guideline | Risk management, overall security posture |
| MITRE ATT&CK | USA (MITRE) | Knowledge base | Threat modeling, detection engineering |
| CIS Controls | USA (CIS) | Prescriptive controls | Practical implementation, hygiene |
| ISO 27001 | International | Certifiable standard | Compliance, enterprise ISMS |

---

## 💡 SOC Analyst Takeaways

- **NIST CSF** = Your security strategy map (Identify → Recover)
- **MITRE ATT&CK** = Your attacker behavior bible (bookmark attack.mitre.org)
- **CIS Controls** = Your prioritized to-do list (start with IG1)
- **ISO 27001** = Your compliance and audit framework
- In a SOC, you'll use ATT&CK daily to map alerts to techniques
- CIS Control 8 (Audit Log Management) is where analysts spend most time

---

## 📚 Resources

| Resource | Link |
|---|---|
| NIST CSF Official | https://www.nist.gov/cyberframework |
| MITRE ATT&CK | https://attack.mitre.org |
| CIS Controls | https://www.cisecurity.org/controls |
| ISO 27001 Overview | https://www.iso.org/isoiec-27001-information-security.html |

---

## 🚀 30-Day Bootcamp Progress

```
Day 01 ✔ Cybersecurity Fundamentals & CIA Triad
Day 02 ✔ Networking Basics & Protocols
Day 03 ✔ OS Security — Linux & Windows
Day 04 ✔ Threat Types & Attack Vectors
Day 05 ✔ Cryptography Essentials
Day 06 ✔ Security Frameworks & Standards  <-- TODAY
Day 07   Identity & Access Management
Day 08   Phase 1 Review & Knowledge Check
...
Day 30   FINAL CAPSTONE
```

**Total XP: 600 / 3700** | Phase 1 Progress: 75%

---

*Part of the CyberOps Academy 30-Day Analyst Bootcamp by @0407ganesh*
