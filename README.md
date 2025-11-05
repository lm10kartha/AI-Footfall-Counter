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

## 📂 Input Video
🎥 [Download Input Video](https://drive.google.com/drive/folders/1zNoHStoIoscCTPVcv_-XDcLYo9kQRksY?usp=sharing)

---

## 📸 Outputs
The `outputs/` folder contains:
- Example screenshots of detections  
- Processed video showing entry and exit counts  

📁 [Watch Output Video and Images on Google Drive](https://drive.google.com/drive/folders/1TU56qFFHgGt4rbg92fx7qs2VgjNVIpiH?usp=sharing)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<lm10kartha>/AI-Footfall-Counter.git
cd AI-Footfall-Counter
```


### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the script
```bash
python footfall_counter.py
```
---

## 📊 Example Use Cases
- Retail stores — count customers entering/exiting to analyze peak hours.
- Offices and malls — monitor employee and visitor flow.
- Events or stadiums — crowd management and safety analytics.
- Smart city applications — pedestrian monitoring.

---

## 👤 Author
**Harikrishnan S Kartha**  
📍 Kochi, Kerala  
🔗 [GitHub Profile](https://github.com/lm10kartha)

---
