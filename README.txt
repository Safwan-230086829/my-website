# Mohammed Ali Safwan Khan
### Electrical & Electronic Engineer • Portfolio Website

[![Portfolio Status](https://img.shields.io/badge/Portfolio-Live-00D4FF?style=flat-square)] [![Degree](https://img.shields.io/badge/BEng%20(Hons)-Aston%20University-AAFF00?style=flat-square)](https://www.aston.ac.uk/)
[![Field](https://img.shields.io/badge/Specialism-Embedded%20%26%20Control-blue?style=flat-square)]()
[![Membership](https://img.shields.io/badge/IET-Student%20Member-orange?style=flat-square)](https://www.theiet.org/)

This repository contains the source code for my professional, high-contrast engineering portfolio. Designed with a retro-cyberpunk aesthetic, it showcases my final-year BEng academic work, hands-on hardware engineering skills, and interactive simulations. 

---

## ⚡ Key Highlights & Features

### 1. Interactive Traction Control System (TCS) Simulator
Embedded directly within this portfolio is a fully-featured, interactive canvas-based simulator showing how control theory regulates vehicle dynamics in real-time.
* **TCS On/Off Toggle:** Contrast raw wheel spin with regulated power.
* **Surface Co-efficient Selector:** Simulate performance on *Ice*, *Wet Lab Floor*, or *Dry Wood*.
* **Real-time Telemetry Graphing:** Visualizes target vs. actual slip ratio ($50\%\rightarrow63\%$ wheel slip reduction on wood surfaces).

### 2. Retro Embedded "Snake" Game
An interactive 8-bit style arcade mini-game built inside a floating overlay to showcase game loop design, state machines, and canvas render loops.

---

## 🛠️ My Engineering Toolchain & Skills

* **Firmware:** C / C++ • C (AVR/Bare-metal) • FreeRTOS • ESP-IDF • Arduino IDE
* **Control Systems:** PID Loop Design • MATLAB • Simulink • SimPowerSystems
* **Hardware & PCB Design:** Schematic Capture • PCB Layout • Proteus • EasyEDA • JLCPCB manufacturing pipeline
* **Digital Logic & Instrumentation:** VHDL • Digital Circuit Design • LabVIEW • Oscilloscopes & Logic Analysers
* **Programming:** Python (Data Analysis & Visualization with Matplotlib) • Object-Oriented Design

---

## 📁 Project Architecture Shown in Portfolio

### 🚗 Featured Project: Traction Control System for an RC Vehicle (Dissertation)
My final-year dissertation focused on developing an active traction management unit for a scaled RC vehicle.
* **MCU Architecture:** Dual-core FreeRTOS on an **ESP32**. Core 0 is dedicated to high-speed sensor acquisition (Hall-effect speed sensors + IMU) while Core 1 computes the discrete PID control loop.
* **Validation:** Verified via an exponential $\mu$-slip tire simulation model built in MATLAB/Simulink prior to hardware manufacturing.
* **Custom PCB:** Features an custom LDO regulator stage, individual Hall-effect sensor power supplies, and on-board SD card SPI interface for high-frequency telemetry data logging.

---

## 🌐 Quick Local Setup & Preview

The portfolio is lightweight, dependency-free, and written in native modern HTML5, CSS3, and JavaScript.

To run it locally:
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)