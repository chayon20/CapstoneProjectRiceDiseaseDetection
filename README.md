# 🌾 Rice Disease Detection & Soil Health Monitoring  

## 📌 Overview  
This project integrates **Deep Learning (DL)** and **IoT-based soil monitoring** to support **precision agriculture**.  
It enables automated detection of rice leaf diseases using image classification models, along with **real-time soil health monitoring** (NPK, pH, temperature, and moisture).  

By combining **computer vision** with **IoT sensors**, the system helps farmers with:  
- Early detection of rice diseases  
- Real-time soil nutrient assessment  
- Data-driven recommendations for fertilizer & pesticide use  
- A web dashboard for monitoring and visualization  

---

## ✨ Features  
- ✅ **Rice Leaf Disease Detection** (10 classes, 97.5% accuracy)  
- ✅ **Soil Health Monitoring** using ESP32 + NPK, pH, DHT22 & moisture sensors  
- ✅ **Deep Learning Models**: EfficientNet-B4, DenseNet121, Xception, MobileNetV3, VGG19, InceptionV3  
- ✅ **Web Application** (Flask + Jinja) for real-time disease & soil reports  
- ✅ **Dashboard** with disease predictions, soil nutrient reports, and recommendations  
- ✅ **Hardware Integration** with IoT sensors and ESP32  

---

## 📂 Dataset  
- **Total Images**: 11,420 rice leaf images  
- **Classes (10)**:  
  - Bacterial Blight  
  - Brown Spot  
  - Leaf Smut  
  - Leaf Blast  
  - Tungro  
  - Sheath Blight  
  - Bacterial Leaf Streak  
  - Hispa  
  - Bacterial Panicle Blight  
  - Healthy Leaf  
- **Format**: JPEG, size 480×640 px  

---

## ⚙️ System Design  
### 🔹 Architecture  
- **Frontend**: Jinja web app (dashboard)  
- **Backend**: Flask REST API (model deployment + database)  
- **IoT Hardware**: ESP32 DevKit + Soil Sensors (NPK, pH, Moisture, DHT22)  
- **Outputs**:  
  - Disease type + confidence score  
  - Soil nutrient analysis & recommendations  

---

## 🧠 Deep Learning Workflow  
- **Data Preprocessing**: Augmentation (flip, rotate, crop, color jitter, Gaussian blur)  
- **Models**: Transfer Learning (EfficientNet, DenseNet, Xception, MobileNet, VGG19)  
- **Ensemble Model** achieved **97.5% accuracy, F1=0.98**  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix  

---

## 🔌 Hardware Setup  
- ESP32 DevKit V1  
- NPK Sensor (RS485)  
- Capacitive Soil Moisture Sensor  
- Soil pH Sensor  
- DHT22 (temperature & humidity)  
- Power Supply (18650 Li-ion + TP4056 charger)  

---

## 📊 Results  
| Model              | Accuracy | F1 Score | Precision | Recall |  
|--------------------|----------|----------|-----------|--------|  
| EfficientNet-B4    | 97.13%   | 0.97     | 0.97      | 0.97   |  
| DenseNet121        | 97.20%   | 0.98     | 0.99      | 0.97   |  
| Xception41         | 97.07%   | 0.97     | 0.96      | 0.97   |  
| MobileNetV3-Large  | 96.73%   | 0.96     | 0.96      | 0.96   |  
| Ensemble Model     | **97.50%** | **0.98** | **0.98**  | **0.98** |  

---

## 💰 Cost Analysis  
Estimated project cost: **28,440 – 52,500 BDT**  
- Hardware (ESP32, sensors, batteries)  
- Cloud GPU access for model training  
- Deployment & maintenance  

---

## 🚀 Future Work  
- Develop a **mobile app** for field deployment  
- Integrate **drone-based imaging** for large-scale monitoring  
- Expand dataset for **better generalization**  
- Optimize for **lightweight edge devices**  

---

## 👨‍💻 Authors  
- **Chayon Kumar Das** (ID: 2001015)  
- **Suvro Kumar Das** (ID: 2001021)  
- Supervised by: **Md Toukir Ahmed**, Assistant Professor, Dept. of IoT & Robotics Engineering, Gazipur Digital University  

---

## 📜 License  
This project is developed for **academic and research purposes**.  
Please cite the authors when using this work.  

