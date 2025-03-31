🚗 Vehicle Speed Tracker & Counter (AI-Powered)
Real-time Vehicle Detection, Tracking, and Speed Estimation using YOLOv8 & OpenCV
🌟 Project Overview
This project is an AI-powered vehicle tracking system that uses YOLOv8 and OpenCV to detect, track, and estimate the speed of moving vehicles in real-time.
It applies computer vision techniques to assign unique IDs to each vehicle, track their movement, and measure their speed with high accuracy.

🔥 Features
✅ AI-based vehicle detection using YOLOv8
✅ Real-time vehicle tracking with a unique ID assigned to each car
✅ Speed estimation algorithm using movement analysis across frames
✅ Customizable alert system for over-speeding vehicles
✅ Dynamic visualization overlay displaying speed, count, and detected vehicles

⚙️ Installation & Setup
1️⃣ Clone This Repository
git clone https://github.com/allagarinithin/Vehicle-Speed-Tracker.git
cd Vehicle-Speed-Tracker

2️⃣ Install Dependencies
pip install ultralytics opencv-python numpy

3️⃣ Run the Application

python vehicle_speed_tracker.py

📁 Project Structure

📁 Vehicle-Speed-Tracker
│── 📜 vehicle_speed_tracker.py  # Main AI script
│── 📜 README.md                  # Documentation
│── 📜 requirements.txt           # Required dependencies
🚀 How It Works
YOLOv8 detects vehicles in real-time from the video stream.

AI-powered tracking assigns unique IDs to each detected car.

Motion-based speed estimation calculates vehicle speeds dynamically.

An overlay display visualizes the speed and total car count.

📊 Example Output
Bounding boxes and tracking lines appear around detected vehicles.

The estimated speed of each car (km/h) is displayed in real-time.

A live vehicle counter tracks the number of cars detected.

📌 Next Steps
🔹 Integrate DeepSORT for more accurate multi-object tracking
🔹 Store detection logs in a CSV file for analysis
🔹 Develop a Flask-based web interface to upload videos for processing
🔹 Deploy as a real-time dashboard with OpenCV streaming

💡 Contributing
Feel free to fork this project, create new features, and submit pull requests. Let’s build an AI-powered traffic monitoring system together!