# Tanadol Kamthong

**Computer Engineering @ KMITL · Embedded Systems & Software Developer**

I build systems end to end — from schematic and PCB layout to firmware, backend APIs, and web interfaces. I care about making things that work reliably in the real world: a 100 Hz flight-control loop, an RS-485 warehouse node, or a billing system that a non-technical user can run every month without mistakes.

📍 Bangkok, Thailand · 🎓 B.Eng. Computer Engineering, KMITL (2024–2028) · 💼 Open to software & embedded internships

[![LinkedIn](https://img.shields.io/badge/LinkedIn-TanadolKamthong-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/TanadolKamthong)
[![Email](https://img.shields.io/badge/Email-TanadolKamthong@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:TanadolKamthong@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-promTT-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/promTT)

---

## Tech Stack

| Area | Technologies |
| --- | --- |
| **Languages** | C, C++, Python, TypeScript, JavaScript, VHDL, SQL |
| **Embedded** | STM32 (Cortex-M7), PIC18F, ESP32, ATmega, FPGA (Xilinx), Altium Designer |
| **Interfaces** | UART, SPI, I2C, RS-485, MQTT, PWM, ADC/DAC |
| **Backend** | NestJS, Node.js, Flask, FastAPI, MongoDB, JWT, REST APIs |
| **Frontend** | React, Vite, Tailwind CSS |
| **Tools** | Git, Linux, Docker, OpenCV, PyTorch |

---

## Featured Projects

### 🏢 Apartment Management Platform
A multi-tenant property-management system for owners, admins, and tenants — covering buildings, floors, rooms, contracts, meter readings, billing, and role-based access.
`NestJS` `TypeScript` `MongoDB` `React` `Tailwind CSS` `JWT`

→ [Backend API](https://github.com/promTT/backend) · [Web Frontend](https://github.com/promTT/WEB_APARTMENT)

### 🧾 Automated Apartment Billing CLI
A Python CLI that replaces manual monthly billing: imports meter readings from CSV, validates anomalies, generates Thai-language PDF invoices, splits them into per-room images, and archives each billing cycle safely.
`Python` `PDF generation` `CSV` `Automation`

→ [View repository](https://github.com/promTT/Python-cli-apartment-bill)

### ♻️ Smart Waste Sorting — CP CUP 2025 Proof of Concept
A Raspberry Pi camera classifies waste into seven categories with a PyTorch model; a Flask service handles inference and a barcode workflow, and servos open the matching bin lid.
`Python` `PyTorch` `Flask` `Raspberry Pi` `OpenCV`

→ [View repository](https://github.com/promTT/cp_poc)

### 📚 Data Structures & Algorithms Lab
Clean, from-scratch Python implementations of stacks, queues, linked lists, trees, graphs, searching, and sorting — written as a reference library rather than exam answers.
`Python` `Algorithms` `Data Structures`

→ [View repository](https://github.com/promTT/OOD_Lab)

---

## Hardware & Embedded Projects

- **STM32 Flight Controller** — 1.5 m RC aircraft with a 100 Hz PID loop on hardware timers, FlySky i-BUS parsing via UART RX interrupts, BNO080 9-DOF IMU, failsafe, and anti-windup filtering.
- **Pick-to-Light Warehouse System** — PIC18F nodes on an RS-485 bus receive pick tasks from a master controller and display quantities on 7-segment displays; designed the production PCB in Altium Designer and wrote the node firmware.
- **Dual-FPGA Pen Plotter** — G-code reader on one FPGA streams over UART to a second FPGA driving steppers and servos, with a hardware pause button and live status display, written in VHDL.
- **IoT Solar Streetlight Monitor** — ESP32 retrofit node that measures lamp status and charging efficiency and reports telemetry over MQTT via a cellular module where no internet is available.

---

## Currently

- Studying Computer Engineering at **King Mongkut's Institute of Technology Ladkrabang (KMITL)**, GPA 3.17
- Vice Head of the Hardware Laboratory — mentoring juniors in microcontrollers and embedded systems
- Looking for a **software / embedded engineering internship** where I can own a problem from hardware to shipped software

---

<sub>Bangkok, Thailand · [TanadolKamthong@gmail.com](mailto:TanadolKamthong@gmail.com) · [LinkedIn](https://www.linkedin.com/in/TanadolKamthong)</sub>
