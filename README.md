# 🚗 Vehicle Speed Tracker & Counter (AI-Powered)

Real-time **Vehicle Detection, Tracking, and Speed Estimation** using **YOLOv8 & OpenCV**

---
## 🌟 Project Overview
This project is an **AI-powered vehicle tracking system** that utilizes **YOLOv8** and **OpenCV** to detect, track, and estimate the speed of moving vehicles in real-time.

### 🔍 Key Features:
- ✅ **AI-based vehicle detection** using YOLOv8
- ✅ **Real-time tracking** with unique IDs assigned to each vehicle
- ✅ **Speed estimation algorithm** using movement analysis across frames
- ✅ **Customizable alert system** for over-speeding vehicles
- ✅ **Dynamic visualization overlay** displaying speed, count, and detected vehicles

---
## ⚙️ Installation & Setup
### 1️⃣ Clone This Repository
```bash
git clone https://github.com/allagarinithin/Vehicle-Speed-Tracker.git
cd Vehicle-Speed-Tracker
```

### 2️⃣ Install Dependencies
Ensure you have Python installed, then install the required packages:
```bash
pip install ultralytics opencv-python numpy
```

### 3️⃣ Run the Application
```bash
python vehicle_speed_tracker.py
```

---
## 📁 Project Structure
```
📁 Vehicle-Speed-Tracker
│── 📜 vehicle_speed_tracker.py  # Main AI script
│── 📜 README.md                  # Documentation
│── 📜 requirements.txt           # Required dependencies
```

---
## 🚀 How It Works
1️⃣ **YOLOv8 detects vehicles** in real-time from the video stream.

2️⃣ **AI-powered tracking assigns unique IDs** to each detected car.

3️⃣ **Motion-based speed estimation** calculates vehicle speeds dynamically.

4️⃣ **An overlay display** visualizes the speed and total car count.

---
## 📊 Example Output
- 🚘 **Bounding boxes and tracking lines** appear around detected vehicles.
- 🏎 **Estimated speed (km/h) of each car** is displayed in real-time.
- 🔢 **Live vehicle counter** tracks the number of detected cars.

---
## 📌 Next Steps
- 🔹 Integrate **DeepSORT** for more accurate multi-object tracking
- 🔹 Store **detection logs in a CSV file** for further analysis
- 🔹 Develop a **Flask-based web interface** for uploading videos
- 🔹 Deploy as a **real-time dashboard with OpenCV streaming**

---
## 💡 Contributing
Feel free to **fork this project**, create new features, and submit **pull requests**. Let's build an **AI-powered traffic monitoring system** together!

🚀 **Star this repository** if you find it useful! 😊

