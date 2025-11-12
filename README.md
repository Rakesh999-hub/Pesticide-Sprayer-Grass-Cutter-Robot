# 🌿 Pesticide Sprayer and Grass Cutter Robot 🤖

## 🔍 Overview
This project is an **IoT-based multipurpose agricultural robot** designed to automate two important farming activities — **pesticide spraying** and **grass cutting**.  
It aims to reduce manual labor and exposure to harmful chemicals while improving the efficiency and safety of agricultural operations.

---

## ⚙️ Features
- Dual functionality: **Grass cutting** and **Pesticide spraying**
- Controlled via **Smartphone (Blynk / Bluetooth / Wi-Fi)**
- **Ultrasonic sensor** for obstacle detection and collision avoidance
- **Adjustable sprayer** nozzle using servo motor
- **Pump control** for pesticide flow
- **Motor driver** for precise DC motor speed control
- Can be upgraded for **autonomous movement**

---

## 🧩 Hardware Components
| Component | Description |
|------------|--------------|
| Arduino UNO / ESP32 | Main control board |
| L298N Motor Driver | Controls DC motors |
| DC Motors | Movement of robot wheels |
| Ultrasonic Sensor (HC-SR04) | Detects obstacles |
| Servo Motor | Controls spray direction |
| Water Pump Motor | Sprays pesticide |
| Cutter Motor & Blade | Cuts grass |
| Battery | Power supply for the robot |
| Chassis, Wheels | Robot base and mobility |
| Wi-Fi / Bluetooth Module | Remote control |

---

## 💻 Software Requirements
- **Arduino IDE** (for programming)
- **Blynk App** (for IoT control)
- **Proteus** (for circuit simulation)
- **Fritzing / EasyEDA** (for schematic drawing)

---

## 🧠 Working Principle
1. The robot moves over the field via **DC motors** controlled by the **L298N driver**.
2. The **Ultrasonic sensor** detects obstacles and prevents collision.
3. The **Sprayer system** activates through a **pump motor** controlled by Arduino.
4. The **Grass cutting mechanism** is powered by a separate DC motor.
5. All controls are managed wirelessly through the **Blynk app or Bluetooth module**.
6. Commands sent from the phone control movement, sprayer, and cutter operations.

---

## 🔋 Block Diagram
