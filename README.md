<h1 align="center">👨‍💻 Niraj Ashtaputre | Red Team & Offensive Security</h1>

<p align="center">
🔍 Exploring Cybersecurity — Ethically<br>
🛠️ Building Security Research & Red Team Tools<br>
🚀 Red Teaming • Recon • Windows Security • Privilege Escalation
</p>

<p align="center">
<img src="https://img.shields.io/badge/Focus-Offensive%20Security-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Windows-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Labs-Authorized%20Only-green?style=for-the-badge">
</p>

---

## 🧰 Featured Projects

| Project | Description | Link |
|---|---|---|
| 🕵️ **SilentSniffer** | Passive network reconnaissance tool built with Scapy | [View Project](https://github.com/niraj-cmd/SilentSniffer) |
| 🧨 **GhostAccess** | Privilege-escalation lab and post-exploitation research scripts | [View Project](https://github.com/niraj-cmd/GhostAccess) |
| 🎯 **BackdoorBox** | Persistence and reverse-shell techniques for controlled security labs | [View Project](https://github.com/niraj-cmd/BackdoorBox) |
| ⌨️ **Windows Keyboard Event Monitoring Lab** | Windows API keyboard-event monitoring research using Python `ctypes` | [View Project](https://github.com/niraj-cmd/python-keylogger) |

---

## 🧠 Skills & Tools

![Python](https://img.shields.io/badge/Python-000?style=flat&logo=python)
![Bash](https://img.shields.io/badge/Bash-000?style=flat&logo=gnu-bash)
![Linux](https://img.shields.io/badge/Linux-000?style=flat&logo=linux)
![Windows API](https://img.shields.io/badge/Windows%20API-000?style=flat&logo=windows)
![Scapy](https://img.shields.io/badge/Scapy-000?style=flat)
![Netcat](https://img.shields.io/badge/Netcat-000?style=flat)
![Red Team](https://img.shields.io/badge/Red%20Team-000?style=flat)
![OSINT](https://img.shields.io/badge/OSINT-000?style=flat)
![CTF](https://img.shields.io/badge/CTF-000?style=flat)

---

## 🚀 About Me

- 💻 I create beginner-friendly cybersecurity and red-team tools
- 🔬 Exploring Windows internals and security research
- 🧪 Working with controlled labs and virtual machines
- 🛡️ Interested in offensive security and defensive detection
- 🧠 Learning privilege escalation, persistence, reconnaissance, and malware-analysis concepts
- 🎯 Interested in CTFs, bug bounty, and security research
- 🤝 Open to cybersecurity collaboration and learning

---

# 🔬 Windows Keyboard Event Monitoring Lab

> ⚠️ **Educational & Authorized Security Research Only**

A Python-based Windows security research project demonstrating interaction with the Windows API through `ctypes`.

The project uses `GetAsyncKeyState()` to examine virtual-key states, detect key transitions, convert selected keys into readable representations, buffer events, and demonstrate HTTP communication through a configured Discord webhook.

---

## ✨ Features

- 🪟 Windows API integration using Python `ctypes`
- ⌨️ Virtual-key state monitoring
- 🔄 Key press transition detection
- 🧵 Background worker thread
- 🔒 Thread-safe event buffering
- 📦 JSON payload generation
- 🌐 HTTP POST communication
- 🐍 Python standard-library implementation
- 🧪 Controlled cybersecurity research

---

## ⚙️ Architecture

```text
       🪟 Windows Keyboard
                │
                ▼
       GetAsyncKeyState()
                │
                ▼
       Key State Tracking
                │
                ▼
          Event Buffer
                │
                ▼
       Background Thread
                │
                ▼
          JSON / HTTP
                │
                ▼
       Discord Webhook
