# 🐗 WarPi.G WebUI

A lightweight, real-time **embedded web dashboard** for [WarPi.G Zero2W](https://github.com/rsftomb/warpig) wardriving app, designed for Raspberry Pi (Zero 2W and up).

Built with **plain HTML, CSS, and JavaScript** — no frameworks, no bloat, no cloud dependencies.
_______________________________________________________________________________________

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
_______________________________________________________________________________________

## 🖥️ Target Platform

- Raspberry Pi Zero 2W (primary)
- Raspberry Pi 3 / 4
- Any Linux device capable of serving static HTML

Optimized for:
- HDMI displays
- Small LCD/OLED screens
- Headless / local-network access
_______________________________________________________________________________________

## 🧱 Tech Stack

- **Frontend:**  
  - HTML5  
  - CSS3 (no external libraries)  
  - Vanilla JavaScript  

- **Backend (install and setup WarPi.G first):**  
  - JSON status endpoint (`/status`)
  - Expected to run on the Pi (Python, Go, etc.)
_______________________________________________________________________________________

⚠️ Legal Notice
This software is intended for legal monitoring and research only.
You are responsible for complying with all applicable local, state, and federal laws regarding wireless monitoring and data collection.
Use at your own risk.
_______________________________________________________________________________________

🛠️ Roadmap (Planned)
OLED-specific layout mode
Optional SVG animation / status indicators
Dark/light theme toggle
Configurable endpoint URL
Auth-gated admin mode
_______________________________________________________________________________________

📜 License
This project is released under the MIT License.
Free to use, modify, and distribute.
_______________________________________________________________________________________

🐗 WarPi.G
Built for embedded systems.
Built for the field.
Built to stay offline.
