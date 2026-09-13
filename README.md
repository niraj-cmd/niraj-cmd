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

🧰 Featured Projects

Project

Description

Link

🕵️ SilentSniffer

Passive network reconnaissance tool built with Scapy

View Project

🧨 GhostAccess

Privilege-escalation lab and post-exploitation research scripts

View Project

🎯 BackdoorBox

Persistence and reverse-shell techniques for controlled security labs

View Project

⌨️ Windows Keyboard Event Monitoring Lab

Windows API keyboard-event monitoring research using Python ctypes

View Project

🧠 Skills & Tools











🚀 About Me

💻 I create beginner-friendly cybersecurity and red-team tools

🔬 Exploring Windows internals and security research

🧪 Working with controlled labs and virtual machines

🛡️ Interested in offensive security and defensive detection

🧠 Learning privilege escalation, persistence, reconnaissance, and malware-analysis concepts

🎯 Interested in CTFs, bug bounty, and security research

🤝 Open to cybersecurity collaboration and learning

🔬 Windows Keyboard Event Monitoring Lab

⚠️ Educational & Authorized Security Research Only

A Python-based Windows security research project demonstrating interaction with the Windows API through ctypes.

The project uses GetAsyncKeyState() to examine virtual-key states, detect key transitions, convert selected keys into readable representations, buffer events, and demonstrate HTTP communication through a configured Discord webhook.

✨ Features

🪟 Windows API integration using Python ctypes

⌨️ Virtual-key state monitoring

🔄 Key press transition detection

🧵 Background worker thread

🔒 Thread-safe event buffering

📦 JSON payload generation

🌐 HTTP POST communication

🐍 Python standard-library implementation

🧪 Controlled cybersecurity research

⚙️ Architecture

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

🛠️ Technologies

Technology

Purpose

🐍 Python 3

Main programming language

🪟 Windows API

Keyboard-state interaction

ctypes

Native Windows API access

threading

Background processing

urllib.request

HTTP communication

json

Payload generation

🔍 How It Works

1. Windows API

user32 = ctypes.windll.user32
kernel32 = ctypes.windll.kernel32

The project uses the Windows user32 API for keyboard-state interaction.

2. Keyboard State

user32.GetAsyncKeyState(vk)

Virtual-key states are checked continuously.

3. State Tracking

The program tracks transitions:

UP → DOWN

A detected transition is added to the temporary buffer.

4. Key Mapping

Selected virtual-key codes are converted into readable representations:

[BACKSPACE]
[SHIFT]
[CTRL]
[ALT]
[ESC]
[LEFT]
[UP]
[RIGHT]
[DOWN]
[DELETE]

Letters and numbers are converted into readable characters.

5. Thread-Safe Buffer

The shared buffer is protected using:

buffer_lock = threading.Lock()

6. Background Sender

A daemon thread periodically processes buffered events and demonstrates JSON-based HTTP POST communication using Python's built-in urllib.request.

📁 Repository Structure

python-keylogger/
│
├── keyfinal.py
├── .gitattributes
└── README.md

🚀 Installation

Requirements

Windows 10 / Windows 11

Python 3.x

Authorized test environment

Network access for webhook testing

The supplied code uses Python's standard library and does not require third-party packages.

▶️ Running

Clone the repository:

git clone https://github.com/niraj-cmd/python-keylogger.git

Enter the directory:

cd python-keylogger

Run:

python keyfinal.py

Stop with:

Ctrl + C

🔐 Webhook Security

The source contains a placeholder:

webhook_url = "ur webhook "

🚨 Never commit a real Discord webhook URL, API key, token, password, or other secret to a public repository.

If a webhook has accidentally been exposed:

🚫 Revoke the exposed webhook

🔄 Generate a replacement

🧹 Remove the exposed value from the repository

🔎 Check Git history for previous exposure

Removing a secret from the latest file does not necessarily remove it from Git history.

🧪 Security Research

This project can be used inside an isolated laboratory to study:

Windows API
     ↓
Input Monitoring
     ↓
Process Behavior
     ↓
Thread Activity
     ↓
Network Communication
     ↓
Endpoint Detection

It can help security researchers understand how input-monitoring behavior and unusual outbound communication may be detected by endpoint-security solutions.

🛡️ Responsible Use

✅ Appropriate Uses

Personal cybersecurity laboratories

Windows API learning

Malware-analysis education

Defensive security research

Endpoint-security experiments

Authorized penetration testing

Virtual machines

CTF environments

❌ Do Not Use For

Unauthorized surveillance

Credential theft

Password collection

Cookie or token theft

Monitoring another person's computer

Secret deployment

Security-software evasion

Collecting information without authorization

🎯 Learning Objectives

🐍 Python
   │
   ├── ctypes
   ├── threading
   ├── JSON
   └── urllib
          │
          ▼
     🪟 Windows API
          │
          ▼
   ⌨️ Keyboard Events
          │
          ▼
   🔬 Security Research
          │
          ▼
       🛡️ Defense

📚 Research Topics

Windows Virtual-Key Codes

GetAsyncKeyState

Python ctypes

Windows API

Thread synchronization

HTTP POST requests

JSON APIs

Endpoint Detection & Response

Malware Analysis

Host-Based Monitoring

Windows Internals

📫 Contact

💻 GitHub: niraj-cmd

💼 LinkedIn: Niraj Ashtaputre

⚖️ Disclaimer

All projects in this profile are intended for educational, CTF, laboratory, and authorized cybersecurity research purposes.

Do not use these projects against systems, accounts, networks, or individuals without appropriate authorization.

You are responsible for complying with all applicable laws, regulations, organizational policies, and authorization requirements.
