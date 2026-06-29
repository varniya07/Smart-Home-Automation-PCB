# 🏠 Smart Home Automation PCB

<p align="center">
  <img src="https://img.shields.io/badge/KiCad-9.0-blue?style=for-the-badge&logo=kicad">
  <img src="https://img.shields.io/badge/ESP32-WROOM--32-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/PCB-2%20Layer-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 📖 Overview

This project presents a **custom-designed ESP32-based Smart Home Automation PCB** developed using **KiCad 9**.

The PCB integrates an ESP32 microcontroller, AC-to-DC power conversion, voltage regulation, relay driver circuitry, programming interface, and user controls into a compact two-layer design suitable for IoT-based home automation.

---

# ✨ Features

* ESP32-WROOM-32 Microcontroller
* HLK-PM03 AC-DC Power Module
* AMS1117-3.3V Voltage Regulator
* Relay Driver Circuit
* Boot & Reset Buttons
* UART Programming Header
* Two-Layer PCB
* Compact Layout
* Mounting Holes

---

# 🛠 Software & Tools

* KiCad 9
* Git
* GitHub

---

# 🔩 Hardware Components

* ESP32-WROOM-32
* HLK-PM03 AC-DC Converter
* AMS1117-3.3V Regulator
* Relay
* BC817 Transistor
* LEDs
* Resistors
* Capacitors
* Push Buttons
* Programming Header

---

# 📷 Schematic

<p align="center">
<img src="Images/smart%20home%20automation.svg" width="900">
</p>

---

# ⚙️ Working Principle

1. AC mains is converted into DC using the **HLK-PM03** power module.
2. The **AMS1117-3.3V** regulator supplies stable 3.3V to the ESP32.
3. The ESP32 processes commands received through Wi-Fi.
4. GPIO pins drive the relay through the transistor driver circuit.
5. The relay switches connected home appliances ON/OFF.
6. Boot and Reset buttons are provided for programming and debugging.

---

# 📂 Repository Structure

```text
Smart-Home-Automation-PCB
│
├── Images
│   ├── PCB_Top.png
│   ├── PCB_3D.png
│   └── smart home automation.svg
│
├── Gerber
│
├── KiCad_Project
│   ├── smart home automation.kicad_pro
│   ├── smart home automation.kicad_sch
│   └── smart home automation.kicad_pcb
│
├── README.md
└── LICENSE
```

---

# 📦 Gerber Files

The repository includes complete Gerber and drill files required for PCB fabrication.

Compatible with:

* JLCPCB
* PCBWay
* ALLPCB

---

# 🚀 Applications

* Home Automation
* Internet of Things (IoT)
* Embedded Systems
* Smart Appliance Control
* PCB Design Learning

---

# 📚 Learning Outcomes

Through this project, I learned:

* PCB Design using KiCad
* Schematic Capture
* Component Placement
* PCB Routing
* Design Rule Check (DRC)
* Gerber Generation
* PCB Manufacturing Workflow

---

# 🔮 Future Improvements

* MQTT Integration
* Mobile App Interface
* Energy Monitoring
* OTA Firmware Updates
* Current & Voltage Monitoring

---

# 👩‍💻 Author

**Varniya Bhatnagar**

B.E. Electronics & Communication Engineering
Panjab University

📧 **Email:** [varniyaece@gmail.com](mailto:varniyaece@gmail.com)

🔗 **LinkedIn:**
https://www.linkedin.com/in/varniya-bhatnagar-1ab361327/

---

⭐ If you found this project useful, please consider giving it a star!
