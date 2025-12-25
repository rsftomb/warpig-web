# 🐗 WarPi.G WebUI

A lightweight, real-time **embedded web dashboard** for the **WarPi.G** wardriving platform, designed for Raspberry Pi (Zero 2W and up).

Built with **plain HTML, CSS, and JavaScript** — no frameworks, no bloat, no cloud dependencies.

---

## ✨ Features

- 📊 Live system telemetry
  - Build version
  - IP address
  - Uptime
  - CPU usage
- 📡 WiFi monitoring
  - Current detections
  - Total networks seen
  - Rolling SSID list
- 🔵 Bluetooth monitoring
  - Current devices
  - Total devices seen
  - Rolling device list
- 🧭 Tab-based UI (Dashboard / WiFi / Bluetooth)
- 🟢 Hacker-style green-on-black terminal aesthetic
- ⚡ Designed for low-power embedded devices

---

## 🖥️ Target Platform

- Raspberry Pi Zero 2W (primary)
- Raspberry Pi 3 / 4
- Any Linux device capable of serving static HTML

Optimized for:
- HDMI displays
- Small LCD/OLED screens
- Headless / local-network access

---

## 🧱 Tech Stack

- **Frontend:**  
  - HTML5  
  - CSS3 (no external libraries)  
  - Vanilla JavaScript  

- **Backend (external, not included):**  
  - JSON status endpoint (`/status`)
  - Expected to run on the Pi (Python, Go, etc.)
