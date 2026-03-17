# 🚗 Intelligent Driver Alertness Monitoring System  
Using Facial Recognition, ML and IoT

## 📌 Overview
This project presents a real-time driver alertness monitoring system designed for embedded platforms like Raspberry Pi. It uses computer vision techniques to analyze facial features and detect signs of driver fatigue.

The system integrates machine learning and IoT-based communication to provide timely alerts and improve road safety in a cost-effective and portable manner.

---

## 🎯 Objectives
- Detect driver drowsiness in real-time  
- Analyze eye and mouth behavior  
- Trigger alert mechanisms during fatigue  
- Enable remote notification using GSM  

---

## ⚙️ System Architecture
Camera → Face Detection → ROI Extraction → Feature Analysis → Decision Engine → Buzzer + GSM Alert  

Neck Movement Detection: MPU6050 (mounted on neck) → Head tilt / sudden drop detection → Emergency Alert  

---

## 🧠 Methodology
1. Capture real-time video using camera module  
2. Detect face and extract relevant regions (eyes and mouth)  
3. Compute fatigue-related features (eye closure and mouth movement)  
4. Analyze temporal patterns for drowsiness detection  
5. Trigger alerts and send notifications when fatigue is detected  

---

## 🧩 Technologies Used
- Python  
- OpenCV  
- MediaPipe  
- Embedded Linux (Raspberry Pi OS)  
- smbus2 (I2C communication)  
- pyserial (GSM communication)  

---

## 🔌 Hardware Components
- Raspberry Pi  
- Camera Module  
- MPU6050 Accelerometer (Neck-mounted)  
- SIM900A GSM Module  
- Buzzer  

---

## 🚨 Features
- Real-time fatigue monitoring  
- Visual + physical drowsiness detection  
- In-vehicle alert system  
- SMS notification to vehicle owner  
- Low-cost embedded solution  

---

## ⚠️ Note
Detailed model architecture, training process, and optimization techniques are part of ongoing research work and will be shared after publication.

---

## 📈 Future Enhancements
- GPS-based location tracking  
- Cloud monitoring dashboard  
- Mobile application integration  
- Improved performance in low-light conditions  

---

## 👨‍💻 Authors
- Niladri Dutta  
- Biplab Pratihar  

---

## 📄 License
This project is developed for academic and research purposes.
