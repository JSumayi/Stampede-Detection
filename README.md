# 🚀 Stampede Predictor

A web application for real-time crowd density analysis and stampede risk prediction using AI.

---

## 🎯 Objective

To analyse crowd density from video feeds (live camera or uploaded media) and identify potential stampede risks. The system provides real-time insights and alerts to improve safety in crowded environments.

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Flask (Python)
* **Libraries & Tools:**

  * OpenCV (video processing)
  * Ultralytics YOLO (object detection)
  * NumPy (data processing)
* **Streaming:** Fluvio

---

## ✨ Features

* Real-time crowd analysis from live video
* Multi-camera monitoring dashboard
* AI-based person detection using YOLO
* Heatmap visualisation of crowd density
* Risk level detection (Normal, High, Critical)
* Image and video upload analysis
* CSV report generation
* Audio alerts for critical situations
* Real-time data streaming using Fluvio

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/your-repo.git
cd Stampede-Predictor
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate (Windows)
pip install -r requirements.txt
python app.py
```

---

## 🌐 Usage

* Open browser and go to: `http://127.0.0.1:5000/`
* Upload media or start live camera feed
* View real-time crowd analysis and risk levels
