🚦 TrafficBrain-AI
Real-Time Traffic Analysis, Speed Violation & Smart Enforcement System using YOLOv11

📌 Overview

TrafficBrain-AI is an intelligent real-time traffic monitoring system powered by YOLOv11 object detection that not only analyzes traffic but also enforces rules digitally.

It performs:

Vehicle detection & classification
Smart vehicle counting
Speed estimation & violation detection
Automated challan (e-challan) generation
Road usage distribution analysis
Interactive analytics dashboard

🎯 Key Features

✅ Real-Time Object Detection
Uses YOLOv11s for fast, accurate detection
Detects multiple vehicles simultaneously
✅ Vehicle Classification
🚗 Cars
🏍️ Motorcycles
🚛 Trucks
🚌 Buses
✅ Vehicle Counting System
Counts vehicles crossing a predefined line
Maintains:
Class-wise count
Total vehicle count
✅ Speed Estimation
Tracks object movement across frames
Estimates relative vehicle speed in real-time
🚨 Speed Violation Detection
Threshold-based logic
Color-coded alerts:
🟢 Safe
🔴 Violation
🧾 Challan (E-Ticketing) System — NEW 🚀
Automatically generates challans for violating vehicles
Stores:
Vehicle type
Speed
Timestamp
🛣️ Road Distribution Analysis — NEW 📊
Shows traffic composition:
% of cars vs bikes vs trucks vs buses
Useful for traffic planning & optimization
📊 Dashboard & Output
results.json → raw data
dashboard_combined.html → visualization

Displays:

Vehicle distribution
Violations
Traffic patterns
🧠 Tech Stack
Python
OpenCV
YOLOv11 (Ultralytics)
NumPy
Jupyter Notebook
📂 Project Structure
TrafficBrain-AI/
│── demo_count_vehicles/
│   └── test_videos/
│
│── smart_traffic_combined.ipynb
│── dashboard_combined.html
│── results.json
│── README.md
│── .gitignore

⚙️ How It Works

Input video → frame-by-frame processing
YOLOv11 detects & tracks vehicles
Line crossing → vehicle counting
Movement → speed estimation
Threshold → violation detection
Challan generated for violations
Road usage analyzed
Dashboard visualization generated

🚀 How to Run

1. Clone the repository
git clone https://github.com/Riya1818/TrafficBrain-AI.git
cd TrafficBrain-AI
2. Install dependencies
pip install ultralytics opencv-python numpy
3. Run
jupyter notebook

Open:

smart_traffic_combined.ipynb
⚠️ Note

Large files not included:

YOLO model (.pt)
Video files (.mp4)

👉 Add them manually before running

📊 Output

Annotated real-time video
Vehicle count (class-wise + total)
Speed violations
Auto-generated challans
Traffic distribution insights
Interactive dashboard

🌟 Future Improvements 

Number Plate Recognition (ANPR)
Live CCTV integration
Cloud deployment
Traffic prediction using ML
Smart signal system

📌 Conclusion

TrafficBrain-AI showcases how AI + Computer Vision + Smart Enforcement can build intelligent traffic systems for safer and smarter cities 🚦
