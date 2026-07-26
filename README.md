# Gunshot Location Detection

## 📌 Project Overview
Gunshot Location Detection is a mini project developed for Electronics and Communication Engineering (ECE). The system detects the direction of a gunshot or loud sound using multiple sound sensors connected to an Arduino Uno. By comparing the sound intensity received by each sensor, the system estimates the direction of the sound source.

## 🎯 Objectives
- Detect the direction of a gunshot or loud sound.
- Compare sound signals from multiple sensors.
- Indicate the detected direction using Arduino.
- Demonstrate a simple, low-cost sound detection system.

## 🛠 Components Used
- Arduino Uno
- 3 × KY-038 Sound Sensors
- Breadboard
- Jumper Wires
- Buzzer
- 220Ω Resistor
- USB Cable

## ⚙ Working Principle
1. Three sound sensors are placed in different directions.
2. When a loud sound is detected, each sensor measures the sound intensity.
3. The Arduino compares the sensor readings.
4. The sensor with the highest reading indicates the direction of the sound.
5. The buzzer provides an alert, and the detected direction is displayed through the Serial Monitor.

## 💻 Software Used
- Arduino IDE
- Embedded C (Arduino Programming)

## 📂 Project Features
- Low-cost prototype
- Easy to build
- Real-time sound direction detection
- Suitable for educational demonstrations

## 📸 Output
The system identifies the direction of a loud sound as:
- LEFT
- CENTER
- RIGHT

## 🚀 Future Improvements
- Add GPS for location tracking.
- Use higher-quality microphones for better accuracy.
- Integrate wireless communication for remote monitoring.
- Apply signal processing to reduce background noise.

## 👩‍💻 Author
**Anamika A**  
B.E. Electronics and Communication Engineering (ECE)

---
This project was developed as an academic mini project for learning sound sensing and Arduino-based embedded systems.
