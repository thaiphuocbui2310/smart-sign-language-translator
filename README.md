# Smart Sign Language Translator

> 🏆 **3rd Prize** — SCAPA Competition 2024  
> 📅 Oct 2024 &nbsp;|&nbsp; Team project

---

## 📌 Overview

An **ESP32-based embedded device** that converts spoken or written language into **sign language characters**, displayed on an HMI screen — designed to aid communication for deaf users.

The device leverages **LoRaWAN** for long-range, low-power wireless communication, making it suitable for use in environments without conventional network infrastructure.

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────┐
│            Sign Language Translator System           │
│                                                     │
│  📝 Text Input                                      │
│       │                                             │
│       ▼                                             │
│  📡 LoRaWAN Receiver                                │
│       │                                             │
│       ▼                                             │
│  🔲 ESP32 MCU                                       │
│    ├── Language Analysis Module                     │
│    └── Sign Language Mapping Engine                 │
│       │                                             │
│       ▼                                             │
│  🖥️ HMI Screen                                      │
│    └── Displays sign language characters            │
└─────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Microcontroller | ESP32 |
| Wireless Protocol | LoRaWAN |
| Display | HMI Screen |
| Firmware | C/C++ (ESP32) |
| Testing/Prototyping | Python, Google Colab |

---

## 👨‍💻 My Contributions

- 🔤 **Sign language analysis**: Studied and mapped Vietnamese/English characters to corresponding sign language representations
- 💻 **ESP32 firmware**: Wrote code to receive input language over LoRaWAN and convert it to sign language characters in real time
- 🧪 **Testing**: Validated the character conversion pipeline in Google Colab environment before flashing to hardware

---

## 🏆 Achievement

> **3rd Prize (Third Prize)** — SCAPA Competition  
> October 2024

SCAPA is a student technology competition organized at Danang University of Science and Technology, focusing on innovative IoT and embedded systems solutions.

---

## 👨‍💻 Author

**Bui Thai Phuoc**  
Control and Automation Engineering, DUT  
📧 thaiphuocbui2310@gmail.com  
🔗 [linkedin.com/in/thaiphuocbui](https://linkedin.com/in/thaiphuocbui)  
🐙 [github.com/thaiphuocbui2310](https://github.com/thaiphuocbui2310)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.
