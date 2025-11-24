# Heart Rate & SpO₂ Monitoring System

A real-time embedded system designed to measure Heart Rate and SpO₂ (oxygen saturation) levels using MAX30100/MAX30102 sensors and Arduino/ESP32.  
This project focuses on accurate vital-sign monitoring through sensor calibration, microcontroller programming, and stable signal processing.

---

## 🚀 Project Overview
This project measures two essential physiological parameters:

- **Heart Rate (BPM)**  
- **SpO₂ (Blood Oxygen Saturation %)**  

It uses a pulse-oximeter sensor to capture light absorption variations, processes signals using a microcontroller, and displays real-time results on an LCD/OLED screen.  
The system aims to provide a **low-cost, reliable, and portable** health-monitoring solution.

---

## 🔧 Technologies & Components Used

### **Hardware**
- MAX30100 / MAX30102 Pulse Oximeter Sensor  
- Arduino UNO / ESP32 Microcontroller  
- OLED / LCD Display  
- Connecting Wires  
- USB Cable  

### **Software**
- Embedded C / Arduino IDE  
- (Optional) Python for visualization or data processing  
- GitHub for version control  

---

## ✨ Features
- Real-time Heart Rate & SpO₂ measurement  
- Sensor calibration for improved accuracy  
- Microcontroller-based signal processing  
- Clean OLED/LCD display output  
- Stable and filtered readings  
- Error handling for fluctuating sensor data  
- Portable and low-cost design  

---

## 🧠 How the System Works
1. The MAX3010x sensor emits red and infrared light into the skin.  
2. Blood absorbs different wavelengths depending on oxygen level.  
3. The photodiode captures reflected light and generates raw readings.  
4. Arduino/ESP32 processes the readings using algorithms.  
5. The final Heart Rate & SpO₂ values are shown on a display.  

---

## 🧪 Testing & Validation
To ensure reliable output:

- Sensor values were compared with standard pulse oximeters  
- Noise & fluctuations were minimized through calibration  
- Multiple test subjects were used  
- Error-handling logic was added to improve reading stability  

---

## 📂 Project Structure (Recommended)
