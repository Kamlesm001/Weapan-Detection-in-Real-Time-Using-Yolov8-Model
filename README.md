# 🔫 Real-Time Weapon Detection using YOLOv8  

## 📌 Overview  
This project implements a **real-time weapon detection system** using the **YOLOv8** model. It enhances security by recognizing weapons such as guns and knives in live video feeds and providing **automated alerts**. The system integrates **computer vision** and **deep learning** to improve **public safety** by analyzing CCTV footage in real-time.  

## 🚀 Features  
✅ **Real-Time Detection** – Identifies weapons instantly with high accuracy  
✅ **YOLOv8 Model** – Uses state-of-the-art deep learning techniques  
✅ **Live Webcam & Video Input** – Works with CCTV, live streams, and recorded footage  
✅ **Web-Based UI** – Flask-powered web interface for monitoring detections  
✅ **Optimized Performance** – Runs on **CPU & GPU** for efficient processing  

## 🎯 Applications  
🔹 **Public Safety & Law Enforcement** – Automated surveillance at public spaces  
🔹 **School & Workplace Security** – Early detection of potential threats  
🔹 **Border & Customs** – Identifies illegal weapons in transit  
🔹 **Retail & Private Security** – Prevents armed robberies and unauthorized weapons  

## 🏗️ Project Structure  
📦 Weapon-Detection-YOLOv8 ┣ 📂 static # Static files (CSS, JS, images) ┣ 📂 templates # HTML templates for Flask UI ┣ 📂 weights # Pre-trained YOLOv8 model files ┣ 📜 app.py # Flask web application ┣ 📜 YOLO_Video.py # Video processing and detection logic ┣ 📜 requirements.txt # Dependencies list ┣ 📜 README.md # Documentation


## 🛠️ Installation & Setup  

### 1️⃣ Clone the Repository  
bash
git https://github.com/Kamlesm001/Weapan-Detection-in-Real-Time-Using-Yolov8-Model.git
cd Weapon-Detection-YOLOv8

## 2️⃣ Install Dependencies
pip install -r requirements.txt

## 3️⃣ Run the Flask Web App
python app.py
📍 Open your browser and go to http://127.0.0.1:5000/

📊 Model Performance
YOLOv8 Model Used: yolov8n
Accuracy: 97%
FPS: 30+ (on GPU)
Classes Detected: Guns, Knives, Rifles, Scissors, and other suspicious objects.

