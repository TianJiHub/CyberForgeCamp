# CyberForgeCamp
Hands-on cybersecurity training camp: labs, CTFs, and red team ops for skill-forging.

🇨🇳 中文 | [🇬🇧 English](README_EN.md)

---

# 🛡️ 网络安全小组培训仓库

<div align="center">
  
![Security Banner](https://img.shields.io/badge/Red%20Team-Cyber%20Security-red?style=for-the-badge&logo=kalilinux)
![CTF](https://img.shields.io/badge/CTF-Competition-blue?style=for-the-badge&logo=ctftime)
![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)

**从入门到实战 | 技能树全覆盖 | 红队思维养成**

[📖 课程导览](#-课程导览) • [🚀 快速开始](#-快速开始) • [🗂️ 目录结构](#️-目录结构) • [🤝 贡献指南](#-贡献指南)

</div>

---

## ✨ 关于仓库

本仓库是 **Aegis CyberKnights（青海大学网络安全小组）** 的核心培训资源库，旨在为社团成员提供系统化的网络安全技能培训，涵盖：

- 🔐 **基础技能**：Linux、网络协议、Web前后端安全、数据库安全、密码学
- 🏆 **CTF竞赛**：PWN、Reverse、Crypto、Web、Misc 全题型训练
- 🎯 **红队渗透**：信息收集、漏洞利用、内网渗透、免杀技术
- 🧪 **实战演练**：靶机实战、CTF真题复盘、红队模拟演练

无论你是零基础小白还是已有经验的老手，这里都有适合你的学习路径。

---

## 🧭 推荐学习路径

> **⚠️ 重要**：目录按技能分类，但建议按以下顺序学习，避免跳跃造成基础不牢。

| 阶段 | 学习内容 | 对应目录 |
| :---: | :--- | :--- |
| 0️⃣ | **环境配置 + 网络安全介绍** | `00-Basics/Environment_Setup/`<br>`00-Basics/Security_Intro.md` |
| 1️⃣ | **Linux基础命令与脚本** | `00-Basics/Linux/` |
| 2️⃣ | **计算机网络基础（TCP/IP、Wireshark）** | `00-Basics/Network/` |
| 3️⃣ | **Python安全编程** | `00-Basics/Python/` |
| 4️⃣ | **Web前后端基础（HTML/JS/PHP）** | `00-Basics/HTML/`、`JavaScript/`、`PHP/` |
| 5️⃣ | **数据库安全基础（MySQL）** | `00-Basics/MySQL/` |
| 6️⃣ | **密码学基础** | `00-Basics/Crypto/` |
| 7️⃣ | **CTF入门（Web、Misc）** | `01-CTF/Web/`、`01-CTF/Misc/` |
| 8️⃣ | **CTF进阶（Pwn、Reverse、Crypto）** | `01-CTF/Pwn/`、`Reverse/`、`Crypto/` |
| 9️⃣ | **红队基础（信息收集、漏洞扫描）** | `02-RedTeam/Recon/`、`Exploit/` |
| 🔟 | **红队高阶（内网、免杀）** | `02-RedTeam/Lateral/`、`Evasion/` |
| 🧪 | **实战靶场 & CTF真题** | `03-Labs/`、`05-Contest/` |

> 💡 可根据自身基础跳过某些阶段，但建议至少完成阶段0~3后再挑战CTF或红队内容。

---

## 📚 课程导览

### 按技能领域

| 领域 | 主要内容 | 适合阶段 |
| :--- | :--- | :---: |
| 🖥️ **系统与网络基础** | Linux、计算机网络、Wireshark | 1~2 |
| 🐍 **安全开发** | Python安全脚本、Web前端（HTML/JS）、后端（PHP） | 3~4 |
| 🗄️ **数据库安全** | MySQL基础、SQL注入原理与防御 | 5 |
| 🔐 **密码学** | 古典密码、对称/非对称加密、哈希函数 | 6 |
| 🏁 **CTF竞赛** | Web、Pwn、Reverse、Crypto、Misc全题型 | 7~8 |
| 🎯 **红队渗透** | 信息收集、漏洞利用、内网横向、免杀 | 9~10 |
| 🧪 **实战演练** | VulnHub、HTB、校内靶场、真题复盘 | 11 |

### 按方向
| 阶段 | 方向 | 主要内容 |  适合人群   |
| :---: | :---: | :--- |:-------:|
| 🟢 **Level 0** | 基础筑基 | Linux命令、计算机网络、Python安全编程、虚拟机使用、Web前端基础、PHP/MySQL安全入门 |  全员必修   |
| 🔵 **Level 1** | CTF入门 | 常用工具(Burp/IDA/GDB)、Web基础、隐写术、编码分析 |  初赛选手   |
| 🟡 **Level 2** | CTF进阶 | 堆栈溢出、ROP链、RSA变种、SQL注入绕过、流量分析 |  专赛选手   |
| 🟠 **Level 3** | 红队基础 | 信息收集(OneForAll/nmap)、漏洞扫描、MSF/Cobalt Strike | 渗透测试兴趣者 |
| 🔴 **Level 4** | 红队高阶 | 域渗透、权限维持、免杀、钓鱼攻击、内网横向移动 | 红队预备队员  |

> 💡 建议按顺序学习，但可根据自身基础跳跃选择。

---

## 🚀 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/TianJiHub/CyberForgeCamp.git
cd CyberForgeCamp
```

### 2. 环境准备

- 推荐使用 **Kali Linux** 或 **Parrot OS**（虚拟机或物理机）
- 安装基础工具：
  ```bash
  sudo apt update && sudo apt install python3 python3-pip git vim curl wget nmap burpsuite
  ```

### 3. 学习路径

- 新手：从「推荐学习路径」阶段0开始，逐项阅读文档并完成练习
- 有基础：直接进入感兴趣的技能目录，参考目录内的 README.md 了解先修要求

---

## 🗂️ 目录结构

```text
cyber-training/
├── 00-Basics/                      # 基础技能
│   ├── Linux/                      # Linux命令、权限、脚本
│   ├── Network/                    # TCP/IP、Wireshark分析
│   ├── Crypto/                     # 古典密码、对称/非对称加密
│   ├── Python/                     # 安全脚本编写
│   ├── HTML/                       # HTML安全（XSS、DOM Clobbering、CSP绕过）
│   ├── JavaScript/                 # JavaScript安全（原型链污染、XSS Payload、CSRF）
│   ├── PHP/                        # PHP安全（文件包含、反序列化、RCE、WebShell）
│   ├── MySQL/                      # MySQL安全（SQL注入、权限提升、UDF）
│   ├── Security_Intro.md           # 网络安全介绍（威胁模型、攻击面、法律法规）
│   └── Environment_Setup/          # 环境配置（Kali/Docker/Burp/IDA/IDE配置指南）
├── 01-CTF/                         # CTF竞赛专题
│   ├── Web/                        # SQLi、XSS、SSRF、RCE
│   ├── Pwn/                        # 栈溢出、堆利用、格式化字符串
│   ├── Reverse/                    # IDA、Ghidra、反混淆
│   ├── Crypto/                     # 现代密码、侧信道
│   └── Misc/                       # 取证、流量、隐写
├── 02-RedTeam/                     # 红队渗透测试
│   ├── Recon/                      # 信息收集(主动/被动)
│   ├── Exploit/                    # 漏洞利用与武器化
│   ├── Lateral/                    # 横向移动与权限维持
│   └── Evasion/                    # 免杀与绕过
├── 03-Labs/                        # 实战靶场
│   ├── VulnHub/                    # 精选VulnHub靶机Writeup
│   ├── HTB/                        # HackTheBox退役机攻略
│   └── Internal/                   # 校内自建靶场
├── 04-Resources/                   # 学习资源
│   ├── Books/                      # 推荐PDF书籍
│   ├── Tools/                      # 工具清单与配置
│   └── Cheatsheets/                # 常用命令速查表
└── 05-Contest/                     # 历年CTF真题 & 竞赛复盘
```

---

## 🧪 实战项目

- **每周一练**：每周末发布一个靶机或CTF题目，次周公布Writeup
- **月度内网渗透赛**：模拟企业内网环境，分组对抗
- **红队演练日**：使用Cobalt Strike进行全流程模拟攻击
- **联合CTF**：与兄弟高校合办线上赛（仓库内提供往期题目）

> 📢 具体活动时间请关注社团群公告。

---

## 🤝 贡献指南

我们欢迎每一位成员贡献内容！

### 你可以：

- 📝 提交更优秀的Writeup或解题脚本
- 🛠️ 增加新的工具使用教程
- 🐛 修正现有文档中的错误或过时内容
- 🌟 分享自己整理的速查表/脑图

### 流程：

1. Fork 本仓库
2. 新建你的分支 `git checkout -b feat/add-xxx`
3. 提交修改 `git commit -m "add: xxx writeup"`
4. 推送并创建 Pull Request

> 所有贡献者将出现在仓库的 `CONTRIBUTORS.md` 中。

---

## 📜 许可证

本仓库内容采用 Apache License 2.0 开源，代码和文档可自由使用，但需保留版权声明、免责声明，并注明修改内容（如有）。

---

## 🙌 致谢

- 感谢所有参与内容整理和培训的社团成员

---

<div align="center">
  
**⭐ 如果这个仓库对你有帮助，请点亮右上角的 Star ⭐**

**保持好奇，保持攻击性 —— HACK THE FUTURE**

[🔝 回到顶部](#-网络安全小组培训仓库)

</div>


