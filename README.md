# TrafficBrain AI 🚦
Real-time vehicle detection, classification, and speed violation analysis using YOLO11 + OpenCV.

## Features
- Detects & tracks vehicles (car, bus, truck, motorcycle)
- Counts vehicles crossing a configurable red line
- Estimates live speed and flags violations with colour-coded boxes
- 🔵 Slow  🟢 Safe  🟡 Caution  🔴 Violation
- Supports multiple road types with class-aware speed limits

## Road type speed limits

| Road type           | Car / Motorcycle | Bus / Truck |
|---------------------|-----------------|-------------|
| School / residential| 30 km/h         | 20 km/h     |
| City road           | 50 km/h         | 40 km/h     |
| Main road           | 60–80 km/h      | 50–60 km/h  |
| Highway             | 100–120 km/h    | 80 km/h     |

To switch road type, update `SPEED_LIMITS` in **Cell 4** of the notebook.

## Setup
```bash
git clone https://github.com/your-username/TrafficBrain-AI.git
cd TrafficBrain-AI
pip install ultralytics opencv-python numpy
jupyter notebook smart_traffic_analysis.ipynb
```

## How to run
1. Update the video path in **Cell 3**
2. Set your road type limits in `SPEED_LIMITS` in **Cell 4**
3. Set `PIXELS_PER_METRE` in **Cell 4** for accurate speed readings
4. Run all cells — press `Q` to quit

## Tech stack
Python · OpenCV · YOLO11 · NumPy
