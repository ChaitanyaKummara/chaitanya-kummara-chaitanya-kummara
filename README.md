# Hi there, I'm Kummara Chaitanya! 👋
### R&D Embedded Software Engineer | Automotive Firmware | Hardware-Aware Developer

📍 **Location:** Bengaluru, India  
📧 **Email:** chaitanyahemanth3@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/chaitanya-kummara-202949241](https://www.linkedin.com/in/chaitanya-kummara-202949241)

---

## 🚀 Professional Summary
I am an **Embedded Systems Engineer (2.5+ Years Exp)** specializing in automotive control systems. Unlike standard firmware developers, I bridge the gap between **algorithm design (R&D)**, **hardware validation**, and **production deployment**.

I specialize in **Safety-Critical Lighting (ADB)**, **Ultrasonic Sensing**, and **Industrial Automation Tools**. My work ensures that code doesn't just run—it survives the harsh reality of automotive hardware.

---

## 🛠 Tech Stack

| **Domain** | **Technologies** |
| :--- | :--- |
| **Microcontrollers** | ![PIC32](https://img.shields.io/badge/Microchip-PIC32CZ%20%2F%20PIC18-blue) ![STM32](https://img.shields.io/badge/ST-STM32-03234B) ![ESP32](https://img.shields.io/badge/Espressif-ESP32-red) |
| **Protocols** | ![CAN-FD](https://img.shields.io/badge/Auto-CAN%20%2F%20CAN--FD-orange) ![UART](https://img.shields.io/badge/Protocol-UART%2FSPI%2FI2C-lightgrey) |
| **Languages** | ![C](https://img.shields.io/badge/Embedded-C-00599C) ![Python](https://img.shields.io/badge/Tools-Python%20%28Automation%29-3776AB) |
| **Tools** | ![Git](https://img.shields.io/badge/Tools-PCAN%20%2F%20Logic%20Analyzer-green) ![Platform](https://img.shields.io/badge/IDE-MPLAB%20X%20%2F%20CubeIDE-purple) |

---

## 🏎️ Key Projects (Case Studies)

*Note: Due to NDA compliance, specific source code for commercial automotive projects is not public. Below are architectural overviews of the systems I engineered.*

### 1. Adaptive Driving Beam (ADB) Control System 🚘
**Role:** Firmware Architecture & Algorithm Design  
**Hardware:** PIC32CZ (Automotive Grade) | **Protocol:** CAN-FD

*   **The Challenge:** Prevent high-beam glare for oncoming drivers while maintaining maximum visibility for the host vehicle.
*   **The Solution:**
    *   Developed a geometric mapping engine that processes data from **15+ oncoming vehicles** via CAN-FD.
    *   Implemented **Coordinate Transformation Logic** to map camera objects (X, Y, Z) to LED Matrix segments.
    *   Designed **Failsafe Logic**: Forced immediate fallback to Low Beam (<20ms) upon sensor/CAN timeout.
*   **Impact:** Achieved flicker-free, real-time masking with robust error handling.

### 2. Ultrasonic DEF Level & Concentration Sensing 💧
**Role:** R&D Algorithm Developer  
**Focus:** Physics-Based Signal Processing

*   **The Challenge:** Accurately measuring Diesel Exhaust Fluid (DEF) quality and level inside a vibrating, heated tank.
*   **The Solution:**
    *   Developed a **Time-of-Flight (ToF)** calculation model compensating for fluid temperature drift and acoustic attenuation.
    *   Designed the SPI-driven signal acquisition flow to capture raw echo times.
*   **Impact:** Validated algorithm accuracy across varying mixture concentrations and temperatures.

### 3. Lighting Controller Flashing System (Production Tool) 🏭
**Role:** Full Stack Developer (Python GUI + MCU Firmware)  
**Hardware:** PIC18 Programmer | **Interface:** Python (Tkinter/Serial)

*   **The Challenge:** Programming **200,000+ driver ICs** in a factory environment with zero tolerance for data corruption.
*   **The Solution:**
    *   Built a custom **Python Automation Tool** that controls the programmer via USB-Serial.
    *   Implemented **Batch Processing** and **Dynamic CAN-ID configuration** to speed up the line.
    *   Added automated **Log Generation** and **Post-Flash Verification**.
*   **Impact:** Maximized production throughput and minimized downtime.

### 4. Welma Box – Functional Tester ⚡
**Role:** Project Lead & Developer  
**Hardware:** PIC32CZ + Custom PCB | **Protocol:** CAN

*   **The Challenge:** End-of-Line testing for complex 4-wheeler headlamp assemblies.
*   **The Solution:**
    *   Designed an automated tester that sends specific CAN sequences to validate DRL, High Beam, Low Beam, and Turn Indicators.
    *   Integrated a user-friendly interface for operators to run guided test sequences.
*   **Impact:** Streamlined the validation process, ensuring 100% functionality before shipment.

### 5. PCB Current Validation Tester 🔌
**Role:** Hardware Validation Engineer  
**Hardware:** PIC MCU + Python GUI

*   **The Challenge:** Detecting micro-defects in PCBs by analyzing load current consumption against strict schematic limits.
*   **The Solution:**
    *   Designed firmware for high-precision ADC sampling.
    *   Developed a Python GUI with **QR-Code Project Selection** and automated Pass/Fail reporting.
*   **Impact:** Enabled plant-wide repeatability and reliability in hardware validation.

### 6. Cluster Instrumentation ECU 📉
**Role:** Firmware Engineer  
**Hardware:** PIC18 Series | **Protocol:** I2C & CAN

*   **The Challenge:** Displaying vehicle data (RPM, Battery, Indicators) with zero lag.
*   **The Solution:**
    *   Designed firmware to interpret CAN vehicle data.
    *   Built a robust **I2C driver** for the BU91799KV display driver.
    *   Integrated **DS1307 RTC** for precise timekeeping.
*   **Impact:** Delivered a stable, flicker-free dashboard experience.

---

### 📫 Let's Connect!
I am always open to discussing **Automotive Firmware, Real-time Systems, and Python Automation**. Feel free to reach out via LinkedIn or Email.
