# S.P.O.T – Sensor-based Predictive Operations Tracker

**Presented by TEAM BLUETRONICS – BLAZEA TRIAL 2.0**  
**Problem Statement (PS-3):** Real-Time Tool Health Monitoring in CNC Using AI & Sensor Data

---

## 📌 Introduction
S.P.O.T (Fix-It-Bot) is an **IoT-based predictive maintenance assistant** designed to monitor CNC machines in real time using an **ESP32 microcontroller** and multiple sensors (temperature, vibration, sound, and current).  
It leverages **AI and machine learning** to detect anomalies and predict failures, enabling **proactive maintenance**.  

🔹 Provides **real-time alerts** via a dashboard, UI, buzzer, and LEDs  
🔹 Helps **reduce downtime, lower maintenance costs, and improve productivity**  
🔹 Combines **IoT, AI, and edge computing** for a scalable, cost-effective solution  

---

## 🛠️ Hardware Components
- **ESP32** – Microcontroller (central unit)  
- **DS18B20** – Temperature sensor  
- **ADXL345** – Accelerometer (vibration detection)  
- **LM393** – Sound sensor  
- **ACS712** – Current sensor  
- **Stepper Motor + Scrap DVD** – CNC machine model  
- **Buzzer and LEDs** – Local alert system  

---

## 💻 Software Components
- **Arduino IDE** – ESP32 programming  
- **Random Forest ML Model** – Machine learning for anomaly detection  
- **Google Colab** – Training & preprocessing datasets  
- **ThinkSpeak** – IoT data visualization and cloud updates  
- **Google Apps Script with Google Sheets** – Data logging & timestamping  
- **Firebase** – Storage and mobile dashboard integration  

---

## 📊 Block Diagram
1. **Sensors** collect data (temperature, vibration, sound, current).  
2. **ESP32** formats and transmits data.  
3. **Google Sheets & Apps Script** log data.  
4. **Random Forest Model** analyzes data for anomalies.  
5. **UI + ThinkSpeak** display graphs, health %, and predictions.  
6. **Buzzer & LEDs** provide real-time local alerts.  

---

## ⚙️ Working
1. **Data Acquisition** – ESP32 continuously reads data from sensors.  
2. **Cloud Upload** – JSON payload sent to Google Sheets via cloud.  
3. **ML Analysis** – Random Forest model trained on historical data.  
4. **Prediction** – Detects abnormal vibration, current spikes, or temperature rise.  
5. **Alerts & Visualization** –  
   - Mobile device shows health trends via ThinkSpeak.  
   - LEDs & buzzer alert operators in real time.  

---

## 🤖 Machine Learning Model
- **Algorithm:** Random Forest (ensemble learning with multiple decision trees).  
- **Input Features:** vibration, spindle load, acoustic levels, temperature, current.  
- **Output:** Fault probability & predicted failure location.  
- **Advantages:**  
  - High accuracy  
  - Reduced overfitting  
  - Reliable in diverse industrial environments  

---

## 🚀 Applications
- Industrial Predictive Maintenance  
- Cost-Effective Tool Health Monitoring  
- Data-Driven Insights for CNC Machines  
- Remote Monitoring & Alerts  
- Scalable & Versatile System  
- Safer & More Reliable Operations  
- Educational & Research Tool  

---

## 📌 Conclusion
S.P.O.T (Fix-It-Bot) is a **transformative AI-powered predictive maintenance solution** that helps industries shift from **reactive** to **proactive maintenance**.  
By combining **IoT sensors, machine learning, and real-time monitoring**, it reduces unexpected downtime, improves safety, and boosts overall productivity.  

> “Let’s revolutionize industrial maintenance together!”

---

## 👥 Team Bluetronics
Developed as part of **Blazea Trial 2.0 Hackathon Project**  
