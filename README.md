<div align="center">

# 🤖 Sentinel AI

### Endpoint Security System with Continuous Face Verification

<p>
  <img src="https://img.shields.io/badge/C++17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/dlib-008000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Telegram_Bot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>
</p>

> 🔒 **Source code is private.** This repository describes the project.

</div>

---

## What it does

Sentinel AI runs in the background on a laptop and keeps checking that the person in front of the camera is the owner. When an unrecognised face appears, it locks the machine, records the event and alerts the owner on Telegram.

---

## ✨ Features

| Feature | Details |
|---------|---------|
| **Face verification** | Real-time recognition using dlib ResNet 128-D face embeddings |
| **Auto-lock** | Locks the laptop when an unrecognised face is detected |
| **Tamper detection** | Detects a blurred, dark or covered camera and multiple people in frame |
| **Kill switch** | Identity recovery through hash-verified security questions |
| **Remote control** | Telegram bot for lock/unlock, live capture and video recording |
| **Activity log** | CSV export of every security event across 16 data fields |

---

## 🛠️ Built with

| Component | Technology |
|-----------|-----------|
| Core | C++17, Rust |
| Computer vision | OpenCV |
| Face recognition | dlib (ResNet face embeddings) |
| Remote control | Telegram Bot API |

---

<div align="center">

**Built by [Harsshh](https://github.com/Soulcynics404)** · [LinkedIn](https://linkedin.com/in/harsshh) · [Portfolio](https://kumar-harsh-portfolio-wheat.vercel.app)

</div>
