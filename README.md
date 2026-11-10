<div align="center">

# 🔐 Cybersecurity - SOC PROJECT - MODULE WIRESHARK (EXTRA)

**🔴 Find an attacker 🔴 Follow TCP Stream 🔴 Hidden data 🔴 Clear text passwords 🔴 Brute force 🔴 VoIP calls**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Wireshark%20v4.6.9-0070C0?style=flat-square&labelColor=000000&logo=wireshark" />
  <img src="https://img.shields.io/badge/Windows%2011-E87500?style=flat-square&labelColor=000000&logo=PCGamingWiki&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Security%20Operations%20Center%20(SOC)-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-192.168.10.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Skill-Virtual%20Labs-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-C00000?style=flat-square&labelColor=000000&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/VoIP%20Calls-404040?style=flat-square&labelColor=C00000&logo=Zoiper&logoColor=white" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-E87500?style=flat-square&labelColor=000000&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Network%20security-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Skill-Critical%20and%20Analytical%20thinking-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/AZIAGBEDO%20KOKOU%20SODJINE%20-%20CCEP-C00000?style=flat-square" />
</p>

---

## 📌 Project Overview

This is a Security Operations Center (SOC) project subdivided in 6 wireshark-lab activities. 

Links to the 6 wireshark-lab activities :

- **SOC LAB 1 :** [Wireshark-lab3](/wireshark-lab3/wireshark-lab3.md)
- **SOC LAB 2 :** [Wireshark-lab4](/wireshark-lab4/wireshark-lab4.md)
- **SOC LAB 3 :** [Wireshark-lab5](/wireshark-lab5/wireshark-lab5.md)
- **SOC LAB 4 :** [Wireshark-lab6](/wireshark-lab6/wireshark-lab6.md)
- **SOC LAB 5 :** [Wireshark-lab7](/wireshark-lab7/wireshark-lab7.md)
- **SOC LAB 6 :** [Wireshark-lab8](/wireshark-lab8/wireshark-lab8.md)

As a SOC analyst in this project, we will investigate 6 live labs. Each lab allows to capture network packets using Wireshark.

We will put into action skills such as Network analysis, Packet inspection, Protocol analysis, Protocol Hierarchy, VoIP, Security mindset, Critical and Analytical thinking, to identify an attacker, follow TCP Stream, rebuid a conversation and read what was sent, find hidden data, usernames, passwords, analyze a VoIP call paquets, play back the call and identify the scammer.

---


## 🎯 Objectives

The main objectives of this project are to:

- Identify the Attacker's IP
- Follow TCP Stream
- Rebuild a conversation and read what was sent
- Find the hidden data
- Find usernames and passwords sent in clear text over HTTP
- Spot the repeated login attempts and find who is guessing passwords (Brut Force Attacker)
- Investigate the capture, play the call and identify the scammer (VoIP call scammer)

---

## 🛡️ Purpose of the Lab

The project provides isolated and controlled environment through the 6 wireshark-labs for Network security learning, SOC skills gaining and authorized Network analysis practices.

It helps gain skills through practical activities :

- Network security
- Wireshark tools
- Packet inspection and analysis
- Protocol Hierarchy
- Protocol analysis
- Follow TCP Stream
- VoIP calls
- Intrusion Detection/Prevention (IDS/IPS)
- Digital Forensics
- Cyber Threat Intelligence (Threat Hunting/Detection/Attribution)
- Critical and Analytical thinking
- Security mindset
- Security-tool experimentation

---

## 🏗️ Lab Architecture

![](/topology-diagram.png)


All the 6 labs are based on this topology diagram.

---

# 🎬 Extra Projects Short Video

A short video on my SOC activities.

https://github.com/user-attachments/assets/95ca40a0-8fd3-4c75-b329-68a18fa75611

---

# 💡 What I practiced

Through this project, I identified suspicious activities in the network traffic, investigated to detect the attacker's IP address, the target's IP address, established a table of observations and facts that confirm the effectiveness of the attack and identified the attack type and its operational technique. I rebuilt the conversation and get the exchanged messages, including credentials and wi-fi password. I found critical hidden data, including a backup server's IP address, password and a downloaded report file. I investigated captured Voice call packets, played back the call to get critical data such as bank card number. I also identified the scammer of the VoIP call. I provided solutions to fix the security issues.

I demonstrated Security Operations Center (SOC) Analysis skills.

The most important skills I demonstrated include:

### 1. Network security

Using Wireshark to capture and analyze network packets helps monitor the network for security purpose. We can then secure what we can see.

### 2. Wireshark tools

I have demonstrated my ability to proficiently use Wireshark tools for **network analysis**, including packet capture, display filtering using the appropriate codes and syntax, TCP Stream following, rebuilding a conversation and read what was sent, finding critical hidden data such as a backup server's IP address, password and a downloaded report file, and VoIP calls playing back.

### 3. Packet inspection and analysis

I inspected and analyzed packets and detected traffic anomalies. I practiced **Packet analysis**, including **TCP Stream** following. I also practiced **Protocol analysis**, especialy the **TCP** (***Three-Way Handshake***), **SIP** and **RTP** protocols.

### 4. Network sniffing

I analyzed the network traffic, detected an unsecure chat and get in plain text credentials and a wi-fi password. I detected unsecure web activities and get a server's IP address, password and the content of a downloaded text file. I detected unsecure VoIP call activities and get critical data such as caller name, responder name and bank card details.

### 5. Intrusion Detection/Prevention (IDS/IPS)

I detected the intrusion of the attacker in the network, the source address and the nature of the attack. Based on those elements, I can respond to that incident by changing the login credentials, blocking the attacker's IP address and closing all ports that are not in service. I can also implement measures to prevent future intrusions.

### 6. Digital Forensics

I established the procedure and the technique of attacks. I identified the source and the type of the attacks. So I can respond to them and implement prevention measures.

### 7. Cyber Threat Intelligence 

The intrusion of the attacker in the network and the port scan activity, the unsecured chat activities, the unsecured web activities, the brute force attack activities and the unsecured VoIP call activities constitute threats for the network security. By analyzing the network and detecting earlier those suspicious and/or malicious activities, I demonstrated Cyber Threat Intelligence skills, including Threat Hunting, Threat Detection and Threat Attribution.

### 8. Critical and Analytical thinking

I demonstrated Critical and Analytical thinking by putting together many observations and details to build a strong argumentation that clearly establish the effectiveness of attacks, their sources, targets and identify the attacks types.

### 9. Security-tool experimentation

Using different command codes to filter and analyze packets and protocoles with Wireshark is a practical way to experiment and master security tools.

### 10. Security mindset

A security mindset in cybersecurity is a proactive, analytical way of thinking. I demonstrated that mindset throughout this project by using curiosity and setting up a proper strategy to analyze traffic, identify suspicious and malicious activities and establish their effectiveness. I proposed solutions to fix and prevent the security issues.

### 11. Documentation

I documented commands / codes, screenshots, tasks and solutions. That is an important part of a professional cybersecurity project.

---

# 🔐 Security & Ethical Use

This project is intended strictly for education purposes only.

>>⚠️ Important: The skills demonstrated in this project must only be used on systems that you own or have explicit permission to test. Do not use the knowledge or the tools to attack unauthorized systems.

---

# 🔗 Tools & Resources

- **Wireshark download:** [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)
- **Wireshark documentation:** [https://www.wireshark.org/docs/](https://www.wireshark.org/docs/)
- **Wireshark community:** [https://www.wireshark.org/blog/](https://www.wireshark.org/blog/)

---

# 👤 Author

**AZIAGBEDO KOKOU SODJINE**\
Cybersecurity Professional B084

LinkedIn: https://www.linkedin.com/in/kokou-sodjin%C3%A8-aziagbedo-434b2949

---

## 📌 Project Information

**Program Name:** Cybersecurity at Networkwalks | **Week:** 01 | **Project:** SOC PROJECT MODULE WIRESHARK (EXTRA) | **Repository:** GitHub



