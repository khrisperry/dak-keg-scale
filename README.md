# 🍺 ESPHome Keg Scale

![ESPHome](https://img.shields.io/badge/ESPHome-Powered-blue?logo=esphome&logoColor=white)
![License](https://img.shields.io/github/license/your-username/keg-scale?style=flat)
![Build](https://img.shields.io/github/actions/workflow/status/your-username/keg-scale/ci.yml?label=CI&logo=github)

A Wi-Fi-connected keg scale that shows **exactly how much beer you have left** without lifting the keg.  
Powered by an ESP8266/ESP32 running ESPHome and an HX711 load cell amplifier.

---

## ✨ Features

|                | Description |
|----------------|-------------|
| 📶 **Wi-Fi Connectivity** | View keg weight from any device on your network. |
| ⚖️ **Two-Point Calibration** | Simple zero point plus two known weights for accurate readings. |
| 📊 **Real-Time Dashboard** | Local web UI shows current weight, % remaining, and last update time. |
| 🔄 **OTA Updates** | Flash new firmware over the air—no cables after the first flash. |
| 🛠 **Modular Hardware** | Works with common load cells, HX711 boards, and ESP8266/ESP32 modules. |

---

## 🚀 Quick Start

1. **Flash** the provided `keg_scale.yaml` to an ESP8266/ESP32.
2. **Power on** the device and connect to the temporary `KegScaleWiFi` network (`MMMMBeer`).
3. Enter your home Wi-Fi credentials in the captive portal and reboot.
4. Find the scale’s IP address, then open the web interface to **calibrate**.
5. Throw a party and keep an eye on the keg level 🍻

---

## 📚 Documentation

| Guide | Purpose |
|-------|---------|
| 📥 **[Installation](guide/installation.md)** | Hardware selection, wiring, and first flash. |
| ⚖️ **[Calibration](guide/calibration.md)** | Step-by-step zero & two-point calibration. |
| 🍺 **[Usage](guide/usage.md)** | Adding kegs, reading stats, OTA updates. |

---

## 🤝 Contributing

Pull requests, bug reports, and feature ideas are welcome!  
Please open an issue to discuss major changes before submitting a PR.

> **Tip:** Want to share a build photo or enhancement? Add it to `examples/` and create a showcase PR.

---

## 📝 License

Distributed under the **MIT License**.  
See `LICENSE` for more information.
