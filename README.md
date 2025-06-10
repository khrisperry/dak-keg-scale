# 🍺 ESPHome Keg Scale

![ESPHome](https://img.shields.io/badge/ESPHome-Powered-blue?logo=esphome&logoColor=white)

A Wi-Fi-connected keg scale that shows **exactly how much beer you have left**—no lifting required.  
Powered by an **ESP32** running ESPHome and an HX711 load-cell amplifier.

---

## ✨ Features

|                | Description |
|----------------|-------------|
| 📶 **Wi-Fi Connectivity** | View keg weight from any device on your network. |
| ⚖️ **Two-Point Calibration** | Simple zero point plus two known weights for accurate readings. |
| 📊 **Real-Time Dashboard** | Local web UI shows current weight, % remaining, and last update time. |
| 🔄 **OTA Updates** | Flash new firmware over the air—no cables after the first flash. |
| 🛠 **Modular Hardware** | Works with standard load cells, HX711 boards, and ESP32 modules. |

---

## 🚀 Quick Start

1. **Flash the Firmware**  
   - Click the **“Install on ESP32”** badge at the top of this page (ESPHome Web Installer).  
   - Follow the prompts to flash the latest firmware—no YAML editing required.

2. **Power On & Connect**  
   - After flashing, power-cycle the ESP32.  
   - Join the temporary Wi-Fi network **`KegScaleWiFi`** (password **`MMMMBeer`**).

3. **Enter Your Wi-Fi Credentials** in the captive portal and reboot.

4. **Find the Scale’s IP**, open the web interface, and **calibrate**.

5. Celebrate and keep an eye on your keg level 🍻

---

## 📚 Documentation

| Guide | Purpose |
|-------|---------|
| 📥 **[Installation](guide/installation.md)** | Hardware selection, wiring, and first flash. |
| ⚖️ **[Calibration](guide/calibration.md)** | Zero & two-point calibration walkthrough. |
| 🍺 **[Usage](guide/usage.md)** | Adding kegs, reading stats, OTA updates. |

---

## 🤝 Contributing

Pull requests, bug reports, and feature ideas are welcome!  
Please open an issue to discuss major changes before submitting a PR.

---

## 📝 License

Distributed under the **MIT License**.  
See `LICENSE` for full details.
