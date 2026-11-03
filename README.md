# 🔧 PCB Design Projects

A collection of **practical electronics, embedded systems, and PCB design projects** developed using **KiCad / eSim**.

This repository brings multiple PCB projects together in one place, covering microcontrollers, motor control, USB, sensors, displays, communication interfaces, power management, and custom development boards.

---

## 📁 Projects

### 1. ESP32 PCB Design

**Custom ESP32 development and interface PCB** designed for embedded applications.

**Key features**

* ESP32 microcontroller
* USB interface
* GPIO expansion
* Power management
* Communication interfaces
* Custom PCB layout
* KiCad schematic, PCB and 3D design

📂 [`ESP32_PCB_DESIGN_ESIM`](./ESP32_PCB_DESIGN_ESIM)

---

### 2. Smart Four-Wheel Controller

A custom **ESP32-based smart 4-wheel robotic controller** integrating motor control, sensors, display and wireless communication.

**Key features**

* ESP32 32-pin DevKit
* L298N motor driver
* 4-wheel motor control
* 12 V motor power input
* 12 V → 5 V buck converter
* HC-SR04 ultrasonic sensor
* MPU6050 IMU
* OLED display
* Wi-Fi
* Bluetooth
* Buzzer
* Status LEDs
* Fuse and power switch
* USB-C programming/interface
* Motor output connectors

📂 [`Smart_Four_wheel_controller`](./Smart_Four_wheel_controller)

---

### 3. AT89S51 USB-C Multi-Interface Development Board

A custom **8051-based development and interface board** designed around the AT89S51 microcontroller.

**Key features**

* AT89S51 microcontroller
* USB-C interface
* Digital I/O expansion
* Communication interfaces
* Status indicators
* External connectors
* Custom power section
* KiCad schematic and PCB layout

📂 [`AT89S51_USB-C_Multi-Interface_Development_Board`](./AT89S51_USB-C_Multi-Interface_Development_Board)

---

### 4. STM32 Base Design — eSim / FOSSEE PCB Project

Custom **STM32-based multi-interface controller board** developed as part of PCB design work using eSim/KiCad.

**Key features**

* STM32 microcontroller
* USB interface
* UART
* SPI
* CAN
* PWM
* Analog and digital I/O
* Bluetooth/Wi-Fi headers
* Power management
* Custom PCB layout
* 4-layer PCB design

📂 [`eSim_PCB_Design_Project_Files`](./eSim_PCB_Design_Project_Files)

---

## 🛠️ Tools & Technologies

| Category           | Tools / Technologies                  |
| ------------------ | ------------------------------------- |
| PCB Design         | KiCad                                 |
| Circuit Simulation | eSim                                  |
| Schematic Design   | KiCad Schematic Editor                |
| PCB Layout         | KiCad PCB Editor                      |
| 3D PCB             | KiCad 3D Viewer                       |
| Version Control    | Git / GitHub                          |
| Microcontrollers   | ESP32, STM32, AT89S51                 |
| Motor Control      | L298N                                 |
| Sensors            | HC-SR04, MPU6050                      |
| Display            | OLED / I²C                            |
| Communication      | USB, UART, SPI, CAN, Wi-Fi, Bluetooth |

---

## 📐 Design Workflow

The projects generally follow this workflow:

```text
Requirements
     ↓
Component Selection
     ↓
Schematic Design
     ↓
ERC Checking
     ↓
Footprint Assignment
     ↓
PCB Layout
     ↓
Design Rule Check (DRC)
     ↓
3D Visualization
     ↓
Gerber / Manufacturing Files
```

---

## 🔍 Design Considerations

The PCB designs focus on practical hardware design principles including:

* Component selection based on datasheets
* Power distribution
* Decoupling and filtering
* Signal routing
* Grounding
* Connector placement
* Protection circuits
* Thermal considerations
* PCB design rules
* ERC and DRC verification
* Manufacturability
* 3D mechanical verification

---

## 📂 Repository Structure

```text
PCB_DESIGN_PROJECTS/
│
├── AT89S51_USB-C_Multi-Interface_Development_Board/
│
├── ESP32_PCB_DESIGN_ESIM/
│
├── Smart_Four_wheel_controller/
│
└── eSim_PCB_Design_Project_Files/
```

Each project contains its own design files, including applicable:

```text
├── Schematic
├── PCB Layout
├── KiCad Project
├── Footprints
├── Symbols
├── 3D Models
├── Documentation
└── Supporting Files
```

---

## 📊 Project Summary

| Project                     | MCU     | Main Purpose                   | PCB     |
| --------------------------- | ------- | ------------------------------ | ------- |
| ESP32 PCB                   | ESP32   | Embedded / Wireless Controller | Custom  |
| Smart Four-Wheel Controller | ESP32   | Robotics / Motor Control       | Custom  |
| AT89S51 Development Board   | AT89S51 | 8051 Development / Interfaces  | Custom  |
| STM32 Base Design           | STM32   | Multi-Interface Controller     | 2-Layer |

---

## 🎯 Objective

The objective of this repository is to develop and document **real-world PCB designs** rather than simple theoretical circuits.

The projects cover different areas of electronics engineering:

* Embedded systems
* PCB design
* Microcontroller hardware
* Power electronics
* Motor control
* Sensor interfacing
* Communication interfaces
* USB connectivity
* Wireless communication
* Hardware debugging
* PCB manufacturing preparation

---

## 🚀 Future Projects

Planned PCB designs include more advanced systems involving:

* Multi-sensor environmental monitoring
* Smart agriculture and irrigation
* Industrial control
* IoT systems
* Data logging
* Wireless sensor networks
* Advanced power management
* Multi-layer PCB designs

---

## 👨‍💻 Author

**Kadarkarai V**

Electronics Engineering — VLSI Design and Technology
Chennai Institute of Technology

### Areas of Interest

* PCB Design
* Embedded Systems
* Electronics Hardware
* Microcontrollers
* IoT
* Hardware Development
* KiCad
* eSim

---

## ⭐ Repository

If you find these PCB designs useful for learning or reference, consider giving the repository a ⭐.

**Designed, developed and documented with KiCad & eSim.**
