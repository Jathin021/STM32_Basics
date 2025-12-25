# 🚀 STM32 Basics using STM32CubeIDE

A **beginner-friendly STM32 learning repository** developed using  
**STM32CubeIDE and STM32CubeMX**, focused on **hands-on embedded systems projects**  
with the **STM32F103 (Blue Pill)** microcontroller.

This repository helps learners understand **GPIO, peripherals, HAL drivers, and
hardware interfacing** through step-by-step practical examples.

---

## 📌 Microcontroller Used
- **STM32F103C6 / STM32F103C8 (Blue Pill)**
- ARM Cortex-M3 | 72 MHz

---

## 🔧 Hardware Requirements
- STM32 Blue Pill Board  
- ST-LINK / V2 Programmer  
- Breadboard & Jumper Wires  
- LEDs with current-limiting resistors  
- Push Button  
- SSD1306 OLED Display (I2C)  
- HC-SR04 Ultrasonic Sensor  

---

## 💻 Software Requirements
- STM32CubeIDE  
- STM32CubeMX  
- ST-LINK Drivers  

---

## 📂 Projects Included

### 🔹 Project 1: Blink On-Board LED
**Objective**  
- Understand basic GPIO configuration and control

**Learning Outcomes**  
- GPIO output configuration  
- HAL delay usage  
- LED ON/OFF control  

---

### 🔹 Project 2: Blink External LED
**Objective**  
- Interface and control external LEDs using GPIO pins

**Learning Outcomes**  
- External LED interfacing  
- GPIO output handling  
- Hardware connection basics  

---

### 🔹 Project 3: Button Controlled LED
**Objective**  
- Control an LED using a push button input

**Learning Outcomes**  
- GPIO input configuration  
- Button state reading  
- Conditional logic in embedded C  

---

### 🔹 Project 4: Interfacing OLED Display (SSD1306 – I2C)
**Objective**  
- Display text on an OLED using I2C communication

**Learning Outcomes**  
- I2C configuration using CubeMX  
- OLED driver integration  
- Text rendering on OLED  

---

### 🔹 Project 5: Distance Measurement using Ultrasonic Sensor
**Objective**  
- Measure distance using HC-SR04 ultrasonic sensor

**Learning Outcomes**  
- Trigger & Echo signal handling  
- Time measurement techniques  
- Distance calculation logic  

---

## 🔌 ST-LINK / V2 Connections

| ST-LINK Pin | Signal | STM32 Blue Pill |
|------------|--------|----------------|
| Pin 7       | SWDIO  | SWDIO          |
| Pin 9       | SWCLK  | SWCLK          |
| Pin 20      | GND    | GND            |
| Pin 1       | VREF   | 3.3V           |

---

## ▶️ How to Use This Repository

1. Clone the repository
   ```bash
   git clone https://github.com/Jathin021/STM32_Basics.git
