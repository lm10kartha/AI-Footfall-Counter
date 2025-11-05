# 🧠 AI Footfall Counter

A Python-based project that uses **YOLOv8** and **OpenCV** to detect and count people entering and exiting through a specific area in real-time.  
The system tracks each person’s movement across frames, defines a virtual counting line, and displays entry/exit counts dynamically.

---

## 🚀 Features
- Detects people in a video stream using **YOLOv8**
- Tracks individuals frame by frame using **OpenCV**
- Defines a **virtual line (ROI)** to count entries and exits
- Displays live entry/exit counts dynamically
- Works on recorded videos or real-time webcam feeds

---

## 🧠 Tech Stack
- **Language:** Python  
- **Libraries:** YOLOv8 (Ultralytics), OpenCV, NumPy, cvzone  
- **Tracking:** Centroid tracking logic

---
## ⚙️ Setup Instructions
### Install dependencies
```bash
pip install -r requirements.txt
