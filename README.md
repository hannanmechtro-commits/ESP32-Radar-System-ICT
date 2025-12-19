# ESP32-Radar-System-ICT
An ESP32-based radar system designed for real-time distance measurement at specific angles. It uses a servo motor for scanning, supports automatic and manual control, hosts a local web interface, and sends live sensor data to ThingSpeak for cloud-based monitoring and visualization in IoT applications.
# ESP32-Based Radar System (ICT Project)

## 📌 Project Overview
This project presents an **ESP32-based radar system** designed for **real-time distance measurement at specific angles** with both **local and cloud-based visualization**.  
The system integrates hardware control, IoT communication, and a web interface to demonstrate core ICT and embedded system concepts.

---

## 🎯 Objectives
- Measure distance at different angles using a rotating sensor
- Implement **automatic and manual scanning**
- Provide **start/stop control**
- Send real-time data to **ThingSpeak**
- Develop a **local web interface** hosted on ESP32

---

## 🧠 System Architecture
The ESP32-S3 acts as the central controller:
- Controls a **servo motor** for angular positioning
- Reads distance from **radar/ultrasonic sensor**
- Sends processed data to **ThingSpeak**
- Hosts a **local web server** for user control

---

## 🔧 Hardware Components
- ESP32-S3 Microcontroller  
- Servo Motor  
- Radar / Ultrasonic Sensor  
- Power Supply  
- Jumper Wires & Resistors  

---

## 💻 Software & Tools
- **Arduino IDE (C/C++)**
- Libraries used:
  - `Servo.h`
  - `WiFi.h`
  - `HTTPClient.h`
  - `ThingSpeak.h`

---

## 🌐 Features
### Local Host Web Interface
- Start / Stop scanning
- Manual angle control
- Real-time response

### ThingSpeak Cloud
- Distance vs Time graphs
- Remote monitoring
- Data logging

---

## ⚠️ Challenges & Solutions
| Challenge | Solution |
|--------|---------|
| Servo jitter | Calibration & stable mounting |
| Sensor noise | Moving average filtering |
| Wi-Fi drops | Robust error handling |

---

## 🚀 Applications
- Robotics (Obstacle detection)
- Industrial automation
- Security systems
- IoT & embedded systems education

---

## 📂 Repository Contents
- `Source_Code/` → ESP32 Arduino code  
- `Web_Interface/` → HTML/CSS/JS files  
- `Presentation/` → Project presentation slides  
- `Circuit_Diagram/` → Hardware connections  
- `Images/` → System visuals  
- `Documentation/` → Project report  

---

## 👨‍🎓 Author
**Hannan**  
BS Mechatronics Engineering  
Air University  

---

## 📜 License
This project is for **educational purposes only**.
