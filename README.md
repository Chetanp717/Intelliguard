# 🔥🔫 INTELLIGUARD: An AI-Enhanced System for Smart Surveillance and Threat Detection 🚧👥

## 📌 Project Overview
This **AI-Powered Surveillance System** is designed to provide real-time monitoring and alerting using **YOLOv11** for various security concerns. The system integrates five key modules:

✅ **Fire Detection** 🔥  
✅ **Weapon Detection** 🔫  
✅ **Work Safety Monitoring** 🚧  
✅ **Crowd Detection** 👥  
✅ **Suspicious Human Activity Detection** 🚨  

Each module is **trained separately** and combined into a unified **real-time monitoring system** using a **Flask-based UI**. The system can process live webcam feeds and send **SMTP email alerts & WhatsApp notifications** when threats or anomalies are detected. 

---
## 📜 Abstract
INTELLIGUARD is a smart AI-powered surveillance system designed to enhance security through real-time monitoring and threat detection. Utilizing the latest YOLOv11 deep learning model, the system can detect fire, weapons, workplace safety violations, crowd anomalies, and suspicious human activities. The model has been trained on publicly available datasets to ensure high accuracy and minimal false positives. The user interface is developed using Flask, providing an intuitive dashboard for live monitoring and alert configurations. With integrated WhatsApp and email alerts, INTELLIGUARD ensures rapid response to security threats in various environments, from industrial workplaces to public spaces.

---
## 🛠️ Features
🔹 **Real-time object detection** using YOLOv11  
🔹 **Multi-module integration** for enhanced security  
🔹 **Flask-based UI** for live monitoring 🌍  
🔹 **Automated alerts** via SMTP Emails & WhatsApp 📧📲  
🔹 **Trained on publicly available datasets** 📊  
🔹 **High accuracy with low false positive rate**  
🔹 **Optimized for edge devices** (Jetson Nano, TPU, etc.)  

---
## 🚀 Tech Stack
- **Framework:** Flask (Python) 🌍
- **Model:** YOLOv11 ⚡
- **Frontend:** HTML, CSS (Flask-based) 🎨
- **Backend:** OpenCV, TensorRT, PyTorch 🖥️
- **Alerts:** SMTP Emails & WhatsApp (Twilio) 📧📲
- **Deployment:** Docker (Optional) 🐳

---
## 🎯 System Architecture
📷 **Webcam Feed** ➝ 🔍 **YOLOv11 Processing** ➝ 🚨 **Threat Detection** ➝ ✉️ **Email & WhatsApp Alerts** ➝ 🖥️ **Flask UI Display**

---
## 📜 Installation & Setup
1️⃣ **Clone the Repository**
```bash
 git clone https://github.com/your-repo/ai-surveillance
 cd ai-surveillance
```
2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```
3️⃣ **Run the Flask App**
```bash
python app.py
```
4️⃣ **Access the UI:** Open `http://127.0.0.1:5000/` in your browser.

---
## 📡 Live Monitoring UI
🎥 View real-time detections via the Flask-based web dashboard.
- The system overlays **bounding boxes** and **labels** on detected threats.
- UI is designed for **smooth and responsive** live streaming.

---
## 📧 Alerts & Notifications
🚨 **When a detection occurs:**
- **Email notifications** are sent automatically with an attached snapshot.
- **WhatsApp alerts** via Twilio ensure instant notification.
- Configurable **alert threshold** to minimize false positives.

---
## 🏗️ Future Enhancements
🔜 Integration with cloud storage ☁️  
🔜 Advanced anomaly detection with LSTMs 📈  
🔜 Edge AI support for low-power devices ⚡  

---
## 🤝 Contributors
👤 **Ms. Sakshi Chougale**  
👤 **Ms. Rutuja Koli**  
👤 **Ms. Vandana Pawar**  
👤 **Mr. Rahul Sankpal**  
👤 **Mr. Chetan Somwanshi**  

📬 **Want to contribute?** Fork the repo and submit a PR! 💡

---
## ⚠️ Disclaimer
This project is intended for **research and security enhancement purposes only**. Ensure compliance with **local laws** before deploying it in real-world scenarios.

---
## ⭐ Show Your Support
If you like this project, give it a ⭐ on GitHub and share your feedback! 💬

---
💻 **Built with passion by IntelliSentinels** 🚀

