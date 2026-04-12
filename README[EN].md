# 🛡️ Cybersecurity Training Repository

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

| Step | Topic | Directory |
| :---: | :--- | :--- |
| 0️⃣ | **Environment Setup + Security Intro** | `00-Basics/Environment_Setup/`<br>`00-Basics/Security_Intro.md` |
| 1️⃣ | **Linux Basics (Commands & Scripting)** | `00-Basics/Linux/` |
| 2️⃣ | **Computer Networking (TCP/IP, Wireshark)** | `00-Basics/Network/` |
| 3️⃣ | **Python for Security** | `00-Basics/Python/` |
| 4️⃣ | **Web Frontend/Backend Basics (HTML/JS/PHP)** | `00-Basics/HTML/`, `JavaScript/`, `PHP/` |
| 5️⃣ | **Database Security Basics (MySQL)** | `00-Basics/MySQL/` |
| 6️⃣ | **Cryptography Basics** | `00-Basics/Crypto/` |
| 7️⃣ | **CTF Entry (Web, Misc)** | `01-CTF/Web/`, `01-CTF/Misc/` |
| 8️⃣ | **CTF Advanced (Pwn, Reverse, Crypto)** | `01-CTF/Pwn/`, `Reverse/`, `Crypto/` |
| 9️⃣ | **Red Team Basics (Recon, Scanning)** | `02-RedTeam/Recon/`, `Exploit/` |
| 🔟 | **Red Team Advanced (Lateral Movement, Evasion)** | `02-RedTeam/Lateral/`, `Evasion/` |
| 🧪 | **Labs & CTF Archives** | `03-Labs/`, `05-Contest/` |

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
cyber-training/
├── 00-Basics/                      # Fundamentals
│   ├── Linux/                      # Linux commands, permissions, scripting
│   ├── Network/                    # TCP/IP, Wireshark analysis
│   ├── Crypto/                     # Classical & modern crypto
│   ├── Python/                     # Security scripting
│   ├── HTML/                       # HTML security (XSS, DOM Clobbering, CSP bypass)
│   ├── JavaScript/                 # JS security (prototype pollution, XSS payloads, CSRF)
│   ├── PHP/                        # PHP security (LFI, deserialization, RCE, webshell)
│   ├── MySQL/                      # MySQL security (SQL injection, privilege escalation, UDF)
│   ├── Security_Intro.md           # Intro to cybersecurity (threat models, attack surfaces, laws)
│   └── Environment_Setup/          # Environment config (Kali/Docker/Burp/IDA/IDE guides)
├── 01-CTF/                         # CTF topics
│   ├── Web/                        # SQLi, XSS, SSRF, RCE
│   ├── Pwn/                        # Stack overflow, heap, format string
│   ├── Reverse/                    # IDA, Ghidra, deobfuscation
│   ├── Crypto/                     # Modern crypto, side-channel
│   └── Misc/                       # Forensics, traffic, steganography
├── 02-RedTeam/                     # Red teaming
│   ├── Recon/                      # Active/passive recon
│   ├── Exploit/                    # Exploitation, MSF, Cobalt Strike
│   ├── Lateral/                    # Lateral movement, persistence
│   └── Evasion/                    # AV/EDR bypass
├── 03-Labs/                        # Hands-on labs
│   ├── VulnHub/                    # VulnHub VM writeups
│   ├── HTB/                        # HackTheBox retired machines
│   └── Internal/                   # Internal club ranges
├── 04-Resources/                   # Learning resources
│   ├── Books/                      # Recommended PDF books
│   ├── Tools/                      # Tool lists and configs
│   └── Cheatsheets/                # Quick reference sheets
└── 05-Contest/                     # Past CTF challenges & writeups
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
- Special thanks to [CTFtime](https://ctftime.org/), [HackTheBox](https://www.hackthebox.com/), [VulnHub](https://www.vulnhub.com/) for their excellent platforms.

---

<div align="center">
  
**⭐ If this repository helps you, please star it! ⭐**

**Stay curious, stay offensive — HACK THE FUTURE**

[🔝 Back to top](#-cybersecurity-training-repository)

</div>
