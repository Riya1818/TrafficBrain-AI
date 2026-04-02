# 🚦 TrafficBrain-AI

### Real-Time Traffic Analysis & Speed Violation Detection using YOLOv11

## 📌 Overview

**TrafficBrain-AI** is an intelligent real-time traffic monitoring system that uses **YOLOv11 object detection** to:

* Detect and classify vehicles (cars, bikes, trucks, buses)
* Count vehicles crossing a defined line
* Estimate relative speed of vehicles
* Detect speed violations using threshold logic
* Provide visual alerts using color coding
* Generate analytics and dashboard outputs

---

## 🎯 Key Features

✅ **Real-Time Object Detection**

* Uses YOLOv11s model for fast and accurate detection

✅ **Vehicle Classification**

* Classifies vehicles into:

  * Cars 🚗
  * Motorcycles 🏍️
  * Trucks 🚛
  * Buses 🚌

✅ **Vehicle Counting System**

* Counts vehicles crossing a predefined line
* Maintains both **class-wise** and **total counts**

✅ **Speed Estimation**

* Calculates relative speed using frame tracking

✅ **Speed Violation Detection 🚨**

* Applies threshold logic
* Color-coded system:

  * 🟢 Green → Safe
  * 🔴 Red → Violation

✅ **Dashboard & Output Files**

* Generates:

  * `results.json` (data output)
  * `dashboard_combined.html` (visual dashboard)

---

## 🧠 Tech Stack

* **Python**
* **OpenCV**
* **YOLOv11 (Ultralytics)**
* **NumPy**
* **Jupyter Notebook**

---

## 📂 Project Structure

```
TrafficBrain-AI/
│── demo_count_vehicles/
│   └── test_videos/
│
│── smart_traffic_combined.ipynb   # Main implementation
│── dashboard_combined.html        # Visualization dashboard
│── results.json                   # Output data
│── README.md
│── .gitignore
```

---

## ⚙️ How It Works

1. Input video is processed frame-by-frame
2. YOLOv11 detects and tracks vehicles
3. Vehicles crossing a predefined line are counted
4. Speed is estimated using object movement
5. Violations are detected using threshold
6. Results are visualized and saved

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Riya1818/TrafficBrain-AI.git
cd TrafficBrain-AI
```

### 2. Install dependencies

```bash
pip install ultralytics opencv-python numpy
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open:

```
smart_traffic_combined.ipynb
```

---

## ⚠️ Note

* Large files like:

  * YOLO model (`.pt`)
  * Video files (`.mp4`)
    are not included due to GitHub size limits

👉 You can download them separately and place in the project folder

---

## 📊 Output

* Real-time annotated video feed
* Vehicle count (class-wise + total)
* Speed violation alerts
* Dashboard visualization

---

## 👩‍💻 Contributors

* **Riya Priyadarshini** – Vehicle Detection, Counting & Classification
* **Bhumika** – Speed Analysis & Violation Detection

---

## 🌟 Future Improvements

* Number plate recognition
* Traffic density prediction using ML
* Cloud-based deployment
* Live CCTV integration

---

## 📌 Conclusion

TrafficBrain-AI demonstrates how **AI + Computer Vision** can be used for smart traffic monitoring, improving road safety and enabling data-driven decision-making.

---
