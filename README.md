# Hybrid Charging System for Electric Vehicles 🔋⚡

A hardware-based hybrid charging system for an electric vehicle that integrates solar power, battery storage, and conventional grid power with automatic switching between operating modes.

## 📌 Project Overview

This project focuses on developing a hybrid charging and propulsion system for an electric vehicle using solar energy as the primary renewable source and grid power as a backup.

The system operates through three modes:

- ☀️ Solar Mode
- 🔋 Battery Mode
- ⚡ Grid Charging Mode

A microcontroller-based switching mechanism enables automatic transition between the available power sources.

## 🎯 Objectives

- Harness solar energy for sustainable EV operation
- Reduce dependency on conventional fuels
- Provide continuous operation when solar energy is unavailable
- Automatically switch between different power sources
- Improve reliability and adaptability under varying conditions

## ⚙️ System Operation

### 1. Solar Mode ☀️

When solar energy is available, the solar panel supplies power and charges the battery. The stored energy can then be used to propel the vehicle.

### 2. Battery Mode 🔋

When solar power is insufficient, the vehicle operates using the stored battery energy to drive the electric motor.

### 3. Grid Charging Mode ⚡

When solar energy is unavailable and the battery requires charging, conventional single-phase grid power is used.

The 230V AC supply is converted to 15V DC through an adapter for battery charging.

## 🔄 Automatic Switching

The system automatically manages the available power sources:

**Solar → Battery → Grid Charging**

This switching mechanism is designed to reduce manual intervention and maintain continuous operation of the vehicle.

## 🧰 Components Used

| Component | Specification |
|---|---|
| Solar Panel | 12V, 5W |
| Battery | 12V, 5Ah |
| Adapter | 230V AC → 15V DC, 2A |
| DC Motors | 12V |
| Buck Converter (LM2596) | 12V DC → 5V DC |
| Arduino UNO | 5V |
| Motor Driver (L298N) | 5–35V, 2A |
| DC Voltage Sensor | 0–25V |
| 16×2 LCD with I2C | 5V |
| Bluetooth Module | 3.3V |
| 4-Channel Relay | 5V |
| Diodes | — |
| SPDT Switch | — |

## 🚗 Prototype

A rear-wheel vehicle prototype was developed using pillar pipes connected to the vehicle base and solar panel structure.

The prototype demonstrates operation using solar energy, stored battery power, and conventional grid charging.

## 📊 Charging Observation

During grid charging:

- Battery voltage: 10.96V → 11.28V
- Charge level: 83% → 91%

## 💰 Prototype Cost

The total listed component cost was:

**₹4,809**

## 👩‍💻 Project Team

**Vissa J S Meghana**  
**Yallabandi Divyanjali**

Department of Electrical & Electronics Engineering  
Shri Vishnu Engineering College for Women

## 📄 Project Documentation

The complete project presentation is available in this repository:

`Hybrid-EV-Charging-System-Presentation.pptx`

## 🚀 Future Scope

Potential improvements can include further development of the automatic power-management system, improved energy monitoring, and enhanced control and communication features.
