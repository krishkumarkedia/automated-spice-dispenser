# 🌶️ Automated Spice Dispenser using 8051 and Arduino

An embedded systems project that automates spice dispensing using a dual-controller architecture. The system integrates an **8051 Microcontroller** and an **Arduino Uno** to control servo motors while utilizing a **load cell with HX711** for accurate real-time weight measurement.

This project demonstrates the integration of embedded systems, sensors, actuators, and serial communication to create a compact and efficient smart kitchen automation solution.

---

## 📖 Project Overview

The **Automated Spice Dispenser** is designed to dispense predefined quantities of spices accurately without manual measurement. A load cell continuously monitors the dispensed weight and provides real-time feedback to stop dispensing once the target quantity is achieved.

The system uses the **8051 Microcontroller** for user interaction and communication, while the **Arduino Uno** controls the servo motors responsible for dispensing spices. The project highlights the practical implementation of embedded systems in automation applications.

---

## ✨ Features

- Automatic dispensing of five different spices
- Real-time weight measurement using a load cell
- Closed-loop feedback for accurate dispensing
- Dual-controller architecture (8051 + Arduino Uno)
- UART communication between controllers
- LCD display for user interaction
- TARE calibration for improved measurement accuracy
- Compact and low-cost embedded automation system

---

## 🛠 Hardware Components

- 8051 Microcontroller
- Arduino Uno
- Servo Motors (5x)
- Load Cell
- HX711 Load Cell Amplifier
- I2C LCD Display
- Push Buttons
- UART Communication Interface
- Regulated Power Supply

---

## 💻 Software & Tools Used

- Embedded C
- Arduino IDE
- Keil uVision
- Proteus Design Suite
- HX711 Library

---

## ⚙️ Working Principle

1. The system initializes all hardware components.
2. The user calibrates the load cell using the **TARE** button.
3. A spice is selected using one of the selection buttons.
4. The **8051 Microcontroller** sends a UART command to the Arduino Uno.
5. The Arduino activates the corresponding servo motor.
6. The spice begins dispensing.
7. The load cell continuously measures the dispensed weight.
8. Once the desired weight is reached, the servo motor stops automatically.
9. The final weight is displayed on the LCD.

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
Arduino Controls Servo
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
 Continue     Stop Servo
      │          │
      └──────────┘
        ▼
Display Final Weight
```

---

## 📂 Repository Structure

```text
Automated-Spice-Dispenser/
│
├── README.md
├── LICENSE
│
├── Report/
│   └── Spice_Dispenser_Report.docx
│
├── Presentation/
│   └── Spice_Dispenser_Presentation.pptx
│

├── Arduino_Code/ (coming soon)
│
└── 8051_Code/ (coming soon)
```

---

## 📊 Results

- Successfully implemented an automated spice dispensing system.
- Achieved accurate dispensing using load-cell feedback.
- Established reliable UART communication between the 8051 and Arduino.
- Ensured stable servo motor operation.
- Demonstrated consistent real-time weight monitoring.

---

## 💡 Applications

- Smart Kitchen Automation
- Automatic Ingredient Dispensing
- Food Processing Industries
- Commercial Restaurants
- Laboratory Ingredient Measurement
- Educational Embedded Systems Projects

---

## 🚀 Future Scope

- Mobile application integration
- Wi-Fi and Bluetooth connectivity
- IoT-based inventory monitoring
- Voice assistant support
- Mobile notifications
- Automatic refill alerts
- Cloud-based monitoring and control

---

## 🎥 Project Demonstration

A complete demonstration of the Automated Spice Dispenser is available on YouTube.

📺 **Demo Video:** https://youtu.be/uS_bVf0X2Ks

---

## 📄 Documentation

This repository currently contains:

- 📘 Project Report
- 📊 Project Presentation
- 🖼 Circuit Diagram
- 🔄 System Flowchart

The Arduino and 8051 source code will be uploaded in a future update.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork this repository and submit a pull request.

---

## 👨‍💻 Author

**Krish**

B.Tech – Electronics and Communication Engineering

Vellore Institute of Technology, Chennai

---

## 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project interesting, consider giving the repository a star!
