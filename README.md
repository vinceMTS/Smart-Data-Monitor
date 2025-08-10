# SmartDataMonitor (working title)

**SmartDataMonitor** is a WPF desktop application written in C#, designed for collecting, displaying, and managing **real-time data from external sources**, such as sensors, embedded systems, and microcontrollers.

> ⚠️ This repository is **preview-only**. The source code is **not publicly available**, as the project is being developed for potential commercial use.

---

## 🎯 Project Goals

- Real-time display of physical variables (e.g., temperature, humidity, voltage, etc.)
- Data logging to CSV or local databases (SQLite)
- Customizable alert system (thresholds, warnings)
- Modular input system supporting multiple data acquisition methods

---

## 👥 Target Users

- **Private users**: monitoring of greenhouses, aquariums, home systems, etc.
- **Makers & hobbyists**: Arduino, ESP32, Raspberry Pi users
- **Small businesses**: labs, artisans, technicians, educators looking for a lightweight monitoring tool

This project is **not** intended for large industrial environments but can serve well in semi-professional or personal use cases.

---

## 🔌 Supported Data Input Methods (planned)

| Method         | Description |
|----------------|-------------|
| **Serial (COM/USB)** | Direct communication with devices like Arduino |
| **TCP/UDP Socket**  | Network-based data from ESP32, Raspberry Pi, etc. |
| **HTTP (REST API)** | Devices send data to local HTTP endpoints |
| **MQTT**            | Lightweight IoT protocol, ideal for distributed sensors |
| **Bluetooth (BLE)** | BLE connection with microcontrollers or mobile devices |
| **File Watcher**     | Polling CSV/TXT files for data from external systems |

Each method is encapsulated in a separate module implementing a shared interface for future extensibility.

---

## 🔧 Technical Overview

- Built with **WPF + MVVM** architecture
- Modular design for data inputs
- Event-driven UI updates
- Configurable and saveable sensor profiles
- Logging system decoupled from visualization

---

## 🚧 Project Status

This project is currently under active development.  
A public demo version (binary only) will be released soon for preview purposes.

---

## 📷 Preview (coming soon)

> Screenshots, mockups, and demo video will be added here.

---

## 📬 Contact

For questions, collaborations, or licensing inquiries, contact:

📧 📘[your email address]  
🔗 📘[LinkedIn or GitHub profile link]

---

## 🛡️ License

This project is protected by a **proprietary license**.  
Use, modification, distribution, or reverse engineering of the code or binaries is **strictly prohibited** without written permission from the author.

See [`LICENSE.txt`](LICENSE.txt) for full details.
