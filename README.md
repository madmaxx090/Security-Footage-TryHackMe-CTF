# Security-Footage-TryHackMe-CTF
CTF write-up for Security Footage room on TryHackMe. Reconstructing video from .pcap stream.
# 🕵️‍♀️ Security Footage – TryHackMe CTF Write-Up

![TryHackMe Badge](https://img.shields.io/badge/TryHackMe-SecurityFootage-red?logo=tryhackme&style=flat-square)

## 🔗 Room Link
[Security Footage – TryHackMe](https://tryhackme.com/room/securityfootage)

---

## 🧠 Challenge Summary

In this CTF, I was given a `.pcap` file that simulated a security camera stream. My goal was to **analyze the network traffic**, extract image frames (JPEGs), reconstruct them into a playable video, and finally **spot the hidden flag**.

---

## 🛠 Tools Used

| Tool       | Purpose                                                                 |
|------------|-------------------------------------------------------------------------|
| Wireshark  | To analyze the `.pcap` file and inspect TCP streams                    |
| binwalk    | To detect embedded JPEG file headers inside the stream data            |
| ffmpeg     | To fix or rebuild the broken video file                                |
| xdg-open   | To quickly open and view media files in Linux                          |

---

## 🧾 Step-by-Step Walkthrough

follow the security footage document 

## 👤 Author

**Name:** Unaiza  
**Role:** Cybersecurity Student | CTF Enthusiast | TryHackMe Explorer  |
**Semester:** 4th Semester – BS Cyber Security  
**LinkedIn:** linkedin.com/in/unaiza-fatima-72451127b
