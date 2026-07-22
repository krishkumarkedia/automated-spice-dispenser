# 🌶️ Automated Spice Dispenser using 8051 Microcontroller and Arduino Uno

An embedded systems project that automates spice dispensing using a dual-controller architecture. The system integrates an **8051 Microcontroller** and an **Arduino Uno** to control servo motors while utilizing a **load cell with the HX711 amplifier** for accurate real-time weight measurement.

---

## 📖 Project Overview

The **Automated Spice Dispenser** is a smart kitchen automation system designed to dispense predefined quantities of spices with high accuracy. The system employs a closed-loop feedback mechanism where a load cell continuously measures the dispensed weight and automatically stops dispensing when the desired quantity is reached.

The project demonstrates the integration of embedded systems, sensors, actuators, and serial communication to create an efficient, low-cost, and reliable automation solution.

---

## ✨ Features

- Automatic dispensing of five different spices
- Real-time weight monitoring using a load cell
- Closed-loop feedback for precise dispensing
- Dual-controller architecture (8051 + Arduino Uno)
- UART communication between controllers
- LCD display for real-time user feedback
- TARE calibration for accurate weight measurement
- Compact and low-cost smart kitchen automation

---

## 🛠️ Hardware Components

- 8051 Microcontroller (Main Controller)
- Arduino Uno
- Servo Motors (5 Units)
- Load Cell
- HX711 Load Cell Amplifier
- I2C LCD Display
- Push Buttons (Spice Selection & TARE)
- Regulated Power Supply

---

## 💻 Software & Tools Used

- Embedded C
- Arduino IDE
- Keil uVision
- Proteus Design Suite

---

## ⚙️ Working Principle

1. Initialize the LCD, UART, HX711 module, and other peripherals.
2. Calibrate the load cell using the **TARE** button.
3. Select the desired spice using one of the push buttons.
4. The 8051 Microcontroller sends a UART command to the Arduino Uno.
5. The Arduino activates the corresponding servo motor.
6. Spice is dispensed while the load cell continuously measures the weight.
7. Once the target weight is achieved, dispensing stops automatically.
8. The LCD displays the measured weight in real time.

---

## 🔄 System Workflow

```text
Initialize System
        │
        ▼
Calibrate Load Cell (TARE)
        │
        ▼
Select Spice
        │
        ▼
8051 Sends UART Command
        │
        ▼
Arduino Controls Servo Motor
        │
        ▼
Dispense Spice
        │
        ▼
Load Cell Measures Weight
        │
        ▼
Target Weight Reached?
      │          │
     No         Yes
      │          │
 Continue     Stop Dispensing
      │          │
      └──────────┘
        ▼
Display Final Weight
```

---

## 📁 Repository Contents

- `README.md`
- `LICENSE`
- `Spice_Dispenser_Report.docx`
- `Spice_Dispenser_Presentation.pptx`
- `Spice_Dispenser_Arduino.ino`
- `Spice_Dispenser_8051.c`

---

## 📊 Results

- Successfully implemented an automated spice dispensing system.
- Accurate dispensing achieved using load-cell feedback.
- Reliable UART communication between the 8051 and Arduino.
- Stable servo motor control.
- Real-time weight monitoring displayed on the LCD.

---

## 💡 Applications

- Smart Kitchen Automation
- Automatic Ingredient Dispensing
- Food Processing Industries
- Educational Embedded Systems Projects
- Laboratory Ingredient Measurement

---

## 🚀 Future Scope

- IoT-based monitoring and control
- Mobile application integration
- Wi-Fi/Bluetooth connectivity
- Voice assistant support
- Inventory monitoring
- Automatic refill notification

---

## 🎥 Project Demonstration

Watch the complete working demonstration on YouTube:

**▶ https://youtu.be/uS_bVf0X2Ks**

---

## 📄 Documentation

This repository includes:

- Complete Project Report
- Project Presentation
- Arduino Source Code
- 8051 Embedded C Source Code
- Project Demonstration Video (YouTube)

---

## 👨‍💻 Author

**Krish**

B.Tech – Electronics and Communication Engineering

Vellore Institute of Technology, Chennai

---

## 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project useful, consider giving this repository a star.
