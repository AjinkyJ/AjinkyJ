# Hi, I'm Ajinkya Jadhav 👋
###########Thank you for reaching out. Much of my recent work in embedded firmware and real-time systems has been developed for proprietary R&D projects and corporate/government initiatives, so the source code is protected under confidentiality agreements and cannot be hosted on a public GitHub repository.################


**Embedded Firmware Engineer** | C-DAC CINE @ IIT Guwahati  
📍 Guwahati, India | 📧 jadhavajinkya1306@gmail.com | [LinkedIn](https://www.linkedin.com/in/ajinkyajadhav77)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## About Me

Embedded firmware engineer with **2+ years of experience** architecting and developing firmware for biomedical, radiation-monitoring, and IoT devices under MeitY R&D programs. I work across the full embedded product lifecycle — from requirement analysis and hardware bring-up to field validation and technical documentation.

I specialize in:
- Low-power firmware architecture for battery-operated IoT devices
- DMA-driven real-time data acquisition pipelines
- Fixed-point DSP and ADC calibration for precision sensing
- BLE (4.2 / 5.0) and Wi-Fi communication stacks
- Bare-metal and FreeRTOS-based firmware

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔧 Technical Skills

| Category | Details |
|---|---|
| **Languages** | Embedded C, C++, Python |
| **RTOS / OS** | FreeRTOS, Bare-metal, Linux (Ubuntu) |
| **Microcontrollers** | STM32F4, STM32L4, STM32H7, STM32WB55, STM32L162, ESP32, ESP32-S3, Vega Aries V3, NodeMCU |
| **Protocols** | UART, USART, SPI, QSPI, I2C, GPIO, USB |
| **Connectivity** | BLE 4.2, BLE 5.0, Wi-Fi, MQTT, TCP/IP |
| **Peripherals** | ADC, DAC, DMA, RTC, PWM, Timers, Interrupt, External Interrupt |
| **Displays** | OLED, TFT (ILI9341), Nextion HMI, LVGL |
| **Sensors** | SiPM, InGaAs, PIN diode, VOC sensors, Load cell (HX711) |
| **Tools & IDEs** | STM32CubeIDE, ESP-IDF, VS Code, Eclipse, Arduino IDE, GitHub |
| **Debug Equipment** | SWD/JTAG debugger, Logic Analyzer, DSO, Digital Multimeter |
| **Design Patterns** | Layered architecture, HAL/Driver separation, State Machine |

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 💼 Work Experience

### Embedded Firmware Engineer (Project Associate)
**C-DAC CINE | IIT Guwahati** — *Feb 2024 – Present*

- Architected and deployed firmware for 4+ embedded and IoT devices under MeitY R&D programs, owning the complete lifecycle from requirement analysis through field validation.
- Delivered BLE-based radiation dosimeter systems, NIR spectroscopy devices, and IoT data acquisition pipelines using DMA-driven frameworks, ADC calibration, and fixed-point DSP.
- Developed low-power firmware for battery-operated IoT devices with peripheral gating to achieve multi-year field life targets.
- Drafted and submitted **5+ embedded R&D project proposals** in collaboration with IITs and government agencies under MeitY funding.
- Collaborated with interdisciplinary teams (biomedical researchers, hardware engineers, data scientists) across concurrent multi-product sprints.

---

## 🏗️ Projects

---

### 🟦 Centre / Product Projects

These are internally driven or client-commissioned projects with defined deliverables and deployment targets.

---

#### 📡 Radiation Survey Meter
**Platform:** STM32 (STM32CubeIDE) | **Role:** Firmware Developer

A portable radiation survey meter based on PIN diode detection, developed as a C-DAC centre product.

- Developed core firmware modules for PIN diode-based radiation detection using STM32.
- Designed firmware for 2.4" TFT display integration via SPI (ILI9341 driver + LVGL library).
- Implemented SD card interface over SPI for local data storage.

**Stack:** `Embedded C` `STM32` `STM32CubeIDE` `PIN diode` `SPI` `TFT Display` `ILI9341` `LVGL`

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### ✈️ Predictive Maintenance System — Indian Air Force
**Platform:** ESP32 | **Role:** Firmware Developer

Condition-monitoring firmware for predictive maintenance deployed for the Indian Air Force.

- Developed sensor integration firmware over GPIO (analog/digital), I2C, and UART interfaces.
- Designed and implemented a 2.8-inch 320×240 TFT UI for real-time sensor data display.
- Debugged and implemented firmware modifications from client feedback and QA validation cycles.

**Stack:** `Embedded C` `ESP32` `VS Code` `I2C` `UART` `GPIO` `TFT Display`

---

#### 🔵 BLE 4.2 Radiation Dosimeter — Hub & Peripheral
**Platform:** Vega Aries V3, STM32L162, Microchip RN4871 | **Role:** Lead Firmware Developer

A BLE-based radiation dosimeter with Hub (Central) and Peripheral firmware for real-time dosimetry data transmission.

- Developed Hub and Peripheral firmware for Aries Vega V3 in Embedded C using Eclipse IDE on Linux.
- Implemented BLE 4.2 communication using the RN4871 module with mobile app integration.
- Developed a 10.1" capacitive touch TFT UI using LVGL.
- Engineered DMA-driven acquisition for PIN diode sensors via UART and integrated sleep mode for low-power operation.
- Debugged BLE communication issues using a BLE sniffer.

**Stack:** `Embedded C` `Vega Aries V3` `STM32L162` `BLE 4.2` `RN4871` `DMA` `UART` `LVGL` `TFT` `Eclipse` `Linux`

---

#### 🏠 Smart Gas AMR — AGCL (Low-Power IoT)
**Platform:** Vega Aries MCU, STM32 | **Role:** Firmware Developer

Automated Meter Reading (AMR) system for gas utility with aggressive low-power design targeting 2-year field life.

- Designed STM32-based firmware with duty-cycled GSM data transmission.
- Engineered low-power architecture using STM32 sleep modes and peripheral gating.
- Achieved a projected **2-year battery life** on a 1200 mAh Li-SOCl₂ cell under optimized transmission schedules.
- Developed a bare-metal task scheduler for application-level firmware control.

**Stack:** `Embedded C` `STM32` `Vega Aries` `GSM` `Low-Power Design` `Sleep Modes` `Bare-Metal` `STM32CubeIDE`

---

### 🟩 R&D Projects (MeitY Funded)

These are government-funded research programs developed in collaboration with IITs and national agencies under MeitY.

---

#### ☢️ BLE 5.0 Radiation Dosimeter Hub & Peripheral
**Platform:** STM32WB55, Vega Aries V3 | **Role:** Lead Embedded Firmware Developer

Research-grade BLE 5.0 dosimeter with real-time wireless data transmission architecture designed for clinical/field deployment.

- Implemented GATT-based BLE 5.0 communication with bonded pairing and secure Peripheral-to-Central data transfer.
- Engineered DMA-driven radiation data acquisition with interrupt-based processing.
- Implemented digital averaging and filtering algorithms for noise immunity and measurement stability.
- Applied State Machine design pattern for deterministic device state management.
- Optimized packet handling to reduce data loss during high-frequency BLE transmission.

**Stack:** `Embedded C` `BLE 5.0` `STM32WB55` `Vega Aries V3` `DMA` `Interrupt-driven design` `GATT` `State Machine`

---

#### 🔬 Portable NIR Spectroscopy — Plastic Identification
**Platform:** STM32WB55 | **Role:** Lead Firmware Designer

Research-grade portable NIR spectroscopy system for plastic composition identification (PET, HDPE, PVC) using InGaAs detectors and custom optical front-end.

- Led end-to-end research, design, and firmware development for the NIR spectroscopy pipeline.
- Architected DMA-driven acquisition with fixed-point DSP for real-time spectral analysis.
- Implemented deep sleep mode and BLE connectivity for low-power portable operation.
- Integrated InGaAs and custom optical front-end for high-sensitivity spectral measurement.

**Stack:** `Embedded C` `STM32WB55` `InGaAs detectors` `Fixed-Point DSP` `DMA` `BLE` `Deep Sleep` `MEMS NIR`

---

#### 🧪 Pratidipt — Fluorescence Intensity Measurement System
**Platform:** ESP32 | **Role:** Firmware Optimization & Signal Processing Engineer

High-precision fluorescence detection system (IIT Guwahati) for biomedical optical measurement applications.

- Designed ADC calibration pipelines and fixed-point digital filtering algorithms to reduce noise and drift in optical measurements.
- Engineered a fixed curve-fitting calibration method for SiPM photon counting sensors.
- Implemented memory-efficient signal processing using fixed-point arithmetic to minimize stack usage.
- Applied HAL/Driver separation for clean hardware abstraction across sensor interfaces.
- Performed timing analysis and stack profiling to ensure deterministic performance.
- Managed UART and I2C data transmission; developed 10.1" Nextion HMI display UI.

**Stack:** `Embedded C/C++` `ESP32` `VS Code` `SiPM sensors` `ADC Calibration` `Fixed-Point DSP` `UART` `I2C` `Nextion HMI` `LVGL`

---

#### 🫁 IoT-Based VOC Breath Analyzer — Oral Cancer Screening
**Platform:** ESP32 | **Role:** Embedded Firmware & Real-Time Data Acquisition

End-to-end firmware for a VOC-based breath analyzer targeting oral cancer biomarker screening.

- Conducted VOC biomarker literature review and sensor selection analysis to guide system architecture.
- Developed real-time data acquisition pipelines with signal processing and noise filtering.
- Implemented MQTT/Wi-Fi communication stack for secure cloud data transmission.
- Optimized ADC sampling, memory allocation, and interrupt handling for accurate VOC measurement.
- Applied layered architecture separating sensor drivers, signal processing, and communication layers.

**Stack:** `Embedded C/C++` `ESP32` `Arduino IDE` `ADC` `MQTT` `Wi-Fi` `FreeRTOS` `Signal Processing` `VOC sensors`

---

#### 🍱 Smart Public Distribution System (PDS) — Automated Grain Dispensing (PoC)
**Platform:** ESP32 | **Role:** Embedded Firmware & IoT Developer

Proof-of-concept for a smart automated grain dispensing system for the Public Distribution System.

- Developed HX711 load cell interface and calibration algorithms for precision weight measurement.
- Implemented a post-dispense event trigger to publish transaction data to an MQTT broker.
- Integrated SMS notification via cloud gateway for user confirmation.

**Stack:** `Embedded C/C++` `ESP32` `HX711 Load Cell` `ADC` `GPIO` `Timers` `MQTT` `Cloud Gateway`

---

## 🎓 Education

| Degree | Institution | Year |
|---|---|---|
| PG Diploma — Embedded System Design | C-DAC, Hyderabad | 2023 |
| M.Sc. Electronics | Fergusson College, Pune | 2017 – 2019 |
| B.Sc. Science | Shivaji University, Kolhapur | 2014 – 2017 |

---

## 📜 Certifications

- Government Official Training on Internet of Things — C-DAC (Aug 2025)
---

*Open to embedded firmware and software roles, R&D collaborations in embedded systems.*
