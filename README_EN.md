# 🛡️ Cybersecurity Training Repository

Hands-on cybersecurity training camp: labs, CTFs, and red team ops for skill-forging.

🇬🇧 English | [🇨🇳 中文](README.md)

---

<div align="center">
  
![Security Banner](https://img.shields.io/badge/Red%20Team-Cyber%20Security-red?style=for-the-badge&logo=kalilinux)
![CTF](https://img.shields.io/badge/CTF-Competition-blue?style=for-the-badge&logo=ctftime)
![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)

**From Zero to Hero | Full Skill Tree | Red Team Mindset**

[📖 Learning Path](#-recommended-learning-path) • [🚀 Quick Start](#-quick-start) • [📂 Directory Structure](#-directory-structure) • [🤝 Contribution Guide](#-contribution-guide)

</div>

---

## ✨ About

This repository is the core training resource for Aegis CyberKnights, the cybersecurity student club of Qinghai University, designed to provide systematic cybersecurity training for our members, including:

- 🔐 **Fundamentals**: Linux, networking, web frontend/backend security, database security, cryptography
- 🏆 **CTF Competitions**: PWN, Reverse, Crypto, Web, Misc — all categories covered
- 🎯 **Red Teaming**: Recon, exploitation, lateral movement, evasion, and full-chain penetration testing
- 🧪 **Hands-on Labs**: VulnHub, HTB, internal ranges, and real CTF challenge walkthroughs

Whether you're a complete beginner or an experienced player, you'll find a suitable learning path here.

---

## 🧭 Recommended Learning Path

> **⚠️ Important**: The directory is organized by skill category, but it is strongly recommended to follow the order below to build a solid foundation.

| Step | Topic | Directory                                   |
| :---: | :--- |:--------------------------------------------|
| 0️⃣ | **Environment Setup** | `00-Basics/00-Environment_Setup/`           |
| 1️⃣ | **Cybersecurity Introduction** | `00-Basics/01-Security_Intro/`              |
| 2️⃣ | **Linux Basics (Commands & Scripting)** | `00-Basics/02-Linux/`                       |
| 3️⃣ | **Computer Networking (TCP/IP, Wireshark)** | `00-Basics/03-Network/`                     |
| 4️⃣ | **Python for Security** | `00-Basics/04-Python/`                      |
| 5️⃣ | **Web Frontend Basics (HTML)** | `00-Basics/05-HTML/`                        |
| 6️⃣ | **Web Frontend Basics (JavaScript)** | `00-Basics/06-JavaScript/`                  |
| 7️⃣ | **Web Backend Basics (PHP)** | `00-Basics/07-PHP/`                         |
| 8️⃣ | **Database Security Basics (MySQL)** | `00-Basics/08-MySQL/`                       |
| 9️⃣ | **Cryptography Basics** | `00-Basics/09-Crypto/`                      |
| 🔟 | **CTF Entry (Web, Misc)** | `01-CTF/01-Web/`、`01-CTF/02-Misc/`          |
| 1️⃣1️⃣ | **CTF Advanced (Pwn, Reverse, Crypto)** | `01-CTF/03-Pwn/`、`04-Reverse/`、`05-Crypto/` |
| 1️⃣2️⃣ | **Red Team Basics (Recon, Scanning)** | `02-RedTeam/01-Recon/`、`02-Exploit/`        |
| 1️⃣3️⃣ | **Red Team Advanced (Lateral Movement, Evasion)** | `02-RedTeam/03-Lateral/`、`04-Evasion/`      |
| 1️⃣4️⃣ | **Labs & CTF Archives** | `03-Labs/`、`05-Contest/`                    |

> 💡 You may skip some steps based on your experience, but it is recommended to complete Steps 0–3 before diving into CTF or Red Team content.

---

## 📚 Course Overview

### By Skill Area

| Area | Topics | Steps |
| :--- | :--- | :---: |
| 🖥️ **System & Networking** | Linux, TCP/IP, Wireshark | 1–2 |
| 🐍 **Secure Development** | Python, HTML/JS, PHP | 3–4 |
| 🗄️ **Database Security** | MySQL, SQL injection | 5 |
| 🔐 **Cryptography** | Classic & modern ciphers, hashing | 6 |
| 🏁 **CTF** | Web, Pwn, Reverse, Crypto, Misc | 7–8 |
| 🎯 **Red Teaming** | Recon, exploitation, lateral, evasion | 9–10 |
| 🧪 **Labs** | VulnHub, HTB, internal ranges | 11 |

### By Level

| Level | Direction | Key Topics | Target |
| :---: | :---: | :--- | :--- |
| 🟢 **Level 0** | Fundamentals | Linux, networking, Python, VM, Web basics, PHP/MySQL | Everyone |
| 🔵 **Level 1** | CTF Entry | Burp/IDA/GDB, Web basics, steganography, encoding | Beginners |
| 🟡 **Level 2** | CTF Advanced | Stack overflow, ROP, RSA variants, SQL injection bypass, traffic analysis | Competitors |
| 🟠 **Level 3** | Red Team Basics | Recon (OneForAll/nmap), scanning, MSF/Cobalt Strike | Pentesting enthusiasts |
| 🔴 **Level 4** | Red Team Advanced | Domain penetration, persistence, evasion, phishing, lateral movement | Red Team candidates |

> 💡 Follow the levels in order, but you can jump based on your current knowledge.

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/TianJiHub/CyberForgeCamp.git
cd CyberForgeCamp
```

### 2. Environment Setup

- Recommended OS: **Kali Linux** or **Parrot OS** (VM or bare metal)
- Install basic tools:
  ```bash
  sudo apt update && sudo apt install python3 python3-pip git vim curl wget nmap burpsuite
  ```

### 3. Learning Path

- **Beginners**: Start from Step 0 in the Recommended Learning Path, read documents and complete exercises.
- **Experienced**: Jump directly to the skill directory you are interested in, and check the `README.md` inside for prerequisites.

---

## 📂 Directory Structure

```text
CyberForgeCamp/
├── 00-Basics/                          # Fundamentals (numbered by recommended order)
│   ├── README.md                        # Overview of basics
│   ├── 00-Environment_Setup/            # Environment setup (Kali/Docker/Burp/IDA/IDE)
│   ├── 01-Security_Intro/               # Cybersecurity intro (threat models, attack surfaces, laws)
│   ├── 02-Linux/                        # Linux commands, permissions, scripting
│   ├── 03-Network/                      # TCP/IP, Wireshark analysis
│   ├── 04-Python/                       # Python security scripting (requests, scapy, pwntools)
│   ├── 05-HTML/                         # HTML security (XSS, DOM Clobbering, CSP bypass)
│   ├── 06-JavaScript/                   # JavaScript security (prototype pollution, XSS payloads, CSRF)
│   ├── 07-PHP/                          # PHP security (LFI, deserialization, RCE, webshell)
│   ├── 08-MySQL/                        # MySQL security (SQL injection, privilege escalation, UDF)
│   └── 09-Crypto/                       # Classical & modern crypto, hash functions
├── 01-CTF/                             # CTF competition topics
│   ├── README.md                        # CTF overview
│   ├── 01-Web/                          # SQLi, XSS, SSRF, RCE
│   ├── 02-Misc/                         # Forensics, traffic, steganography
│   ├── 03-Pwn/                          # Stack overflow, heap exploitation, format string
│   ├── 04-Reverse/                      # IDA, Ghidra, deobfuscation
│   └── 05-Crypto/                       # Modern cryptography, side-channel
├── 02-RedTeam/                         # Red team penetration testing
│   ├── README.md                        # Red team overview
│   ├── 01-Recon/                        # Information gathering (active/passive)
│   ├── 02-Exploit/                      # Exploitation & weaponization (MSF/Cobalt Strike)
│   ├── 03-Lateral/                      # Lateral movement & persistence
│   └── 04-Evasion/                      # Evasion & bypass (AV/EDR)
├── 03-Labs/                            # Hands-on practice ranges
│   ├── README.md                        # Labs overview
│   ├── 01-VulnHub/                      # Selected VulnHub VM writeups
│   ├── 02-HTB/                          # HackTheBox retired machines walkthroughs
│   └── 03-Internal/                     # Internal club-built ranges
├── 04-Resources/                       # Learning resources
│   ├── README.md                        # Resources overview
│   ├── 01-Books/                        # Recommended PDF books
│   ├── 02-Tools/                        # Tool lists & configurations
│   └── 03-Cheatsheets/                  # Quick reference sheets
└── 05-Contest/                         # Past CTF challenges & competition writeups
    └── README.md                        # Contest archive overview
```

---

## 🧪 Practical Activities

- **Weekly Challenge**: A new VM or CTF problem every weekend, writeup published the following week.
- **Monthly Internal Pentesting Competition**: Simulate an enterprise network, team vs team.
- **Red Team Drill Day**: Full attack chain simulation using Cobalt Strike.
- **Joint CTF**: Online competition with partner universities (past challenges are in the repo).

> 📢 Check club announcements for schedules.

---

## 🤝 Contribution Guide

We welcome contributions from all members!

### You can:

- 📝 Submit better writeups or solution scripts
- 🛠️ Add new tool tutorials
- 🐛 Fix errors or outdated content
- 🌟 Share your own cheatsheets / mind maps

### Workflow:

1. Fork this repository
2. Create your branch `git checkout -b feat/add-xxx`
3. Commit your changes `git commit -m "add: xxx writeup"`
4. Push and open a Pull Request

> All contributors will be listed in `CONTRIBUTORS.md`.

---

## 📜 License

This repository is open-sourced under the Apache License 2.0. You are free to use the content, but you must retain the copyright notice, disclaimer, and indicate any changes made (if applicable).

---

## 🙌 Acknowledgements

- Thanks to all club members who contributed to content creation and training.

---

<div align="center">
  
**⭐ If this repository helps you, please star it! ⭐**

**Stay curious, stay offensive — HACK THE FUTURE**

[🔝 Back to top](#-cybersecurity-training-repository)

</div>
