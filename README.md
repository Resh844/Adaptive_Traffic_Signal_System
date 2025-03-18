# 🚦 Adaptive Traffic Signal System using AI/ML

## 📌 Project Description
The number of vehicles on the road is increasing, leading to longer travel times and frequent traffic jams. To address this issue, a better traffic management system is needed to reduce the time spent at intersections. By analyzing traffic in each lane, an automated control system can be developed to dynamically adjust traffic signals based on real-time traffic volume, minimizing unnecessary delays at intersections.

According to research, an average of **243 hours (10 days, 3 hours)** is lost due to traffic congestion in Bangalore. An **automated signaling system** can significantly reduce delays. The first step in building such a system is to accurately assess traffic composition in each lane, allowing for intelligent signal adjustments. This project aims to create a **smart signaling system** by developing a model that can analyze traffic, classify vehicle types, and count them in real time. The collected data will be used to optimize traffic signals efficiently.

## 🎯 Objective
- Reduce **waiting time** at signalized intersections
- Detect and classify vehicles using AI/ML
- Automate **traffic signal optimization** based on vehicle count

##  Features
- Real-time **vehicle detection** using **YOLOv3 & OpenCV**
- Classification of vehicles into categories (cars, trucks, buses, auto-rickshaws, motorbikes)
- **Traffic volume-based signal adjustments**
- **Surveillance camera integration** for live analysis
- **Data-driven traffic management** for better flow

##  Tech Stack
- **Programming Language**: Python
- **AI/ML**: OpenCV, TensorFlow, YOLOv3
- **Dataset**: MS COCO + Custom dataset
- **Backend**: Flask/FastAPI
- **Database**: MySQL/PostgreSQL (Optional)
- **Frontend**: React.js (for Dashboard) (Optional)

## 📍 Data Collection & Model Training
- The input consists of **surveillance camera footage** from intersections at **Town Hall Circle, Tumkur**.
- Three lanes of traffic footage were collected for model testing.
- The model is trained using a **combination of Microsoft's COCO dataset and a custom dataset**.
- The system applies **YOLOv3 for vehicle detection and classification**.
- Background noise is removed, and only **one lane is considered per video**.
- The system outputs the count of different vehicle types in the intersection.

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Resh844/Adaptive_Traffic_Signal_System.git
```

## 📊 Future Enhancements
- **IoT integration** for real-time sensor-based traffic detection
- **Deep Reinforcement Learning** for improved signal control
- **Predictive analytics** to forecast traffic trends and congestion levels

🚀 **Towards smarter and more efficient traffic management!** 🌍
