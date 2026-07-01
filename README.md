# 🚨 AI Crowd Detection & Heatmap Monitoring System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-red?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

### Real-Time Crowd Detection • Density Heatmap • Telegram Alert System

---

Detects people in real-time using **YOLOv8**, generates **crowd density heatmaps**, identifies **high-density zones**, and sends **instant Telegram alerts** whenever overcrowding is detected.

⭐ If you like this project, don't forget to star the repository!

</div>

---

# ✨ Features

- 👤 Real-Time Person Detection using YOLOv8
- 📊 Live Crowd Counting
- 🔥 Dynamic Heatmap Generation
- 🚨 Overcrowding Detection
- 📍 High Density Zone Detection
- 📲 Telegram Alert Notifications
- 🎥 Webcam & Video Support
- ⚙ Adjustable Detection Thresholds
- 🟢 Lightweight & Fast Inference
- 📈 Grid-Based Crowd Density Analysis

---

# 🏗 Project Architecture

```text
              Video / Webcam
                     │
                     ▼
           YOLOv8 Person Detection
                     │
                     ▼
             People Counting
                     │
                     ▼
         Density Grid Calculation
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
     Heatmap Overlay      Crowd Analysis
          │                     │
          └──────────┬──────────┘
                     ▼
          Telegram Alert System
```

---

# 🖥 Output

## Live Detection

✔ Person Detection

✔ Crowd Counter

✔ Heatmap Overlay

✔ High Density Highlight

✔ Telegram Alerts

---

# ⚡ Tech Stack

| Technology | Usage |
|------------|-------|
| Python | Programming Language |
| YOLOv8 | Person Detection |
| OpenCV | Image Processing |
| NumPy | Matrix Operations |
| Requests | Telegram API |
| Python-dotenv | Environment Variables |

---

# 📂 Project Structure

```
AI-Crowd-Detection-System
│
├── detect_final.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── assets
     ├── heatmap.png


---

# ⚙ Installation

Clone Repository

```bash
git clone https://github.com/shahjinay22/Crowd-Detection-System.git
```

Move into project

```bash
cd AI-Crowd-Detection-System
```

Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ Run

### Webcam

```bash
python detect_final.py --video 0
```

### Video

```bash
python detect_final.py --video crowd.mp4
```

---

# ⚙ Command Line Options

| Parameter | Description |
|-----------|-------------|
| --video | Webcam or Video Path |
| --model | YOLO Model |
| --conf | Detection Confidence |
| --grid | Grid Size |
| --hot | High Density Threshold |
| --max_people | Overcrowding Threshold |

Example

```bash
python detect_final.py --video crowd.mp4 --grid 5 --hot 3 --max_people 20
```

---

# 🚨 Alert System

## High Density Zone

Whenever a grid cell exceeds the configured threshold, it is highlighted in **Red** and an alert is generated.

## Overcrowding Alert

If the total number of detected people exceeds the configured limit, the system instantly sends a **Telegram Notification**.

Example

```
🚨 OVERCROWD ALERT

People Detected : 25

Threshold : 20

Time : 2026-07-01
```

---

# 📊 Heatmap Legend

🔵 Low Density

🟡 Medium Density

🔴 High Density

---

# 🎯 Applications

🏟 Stadium Monitoring

🚉 Railway Stations

🏫 College Campus

🏥 Hospitals

🛍 Shopping Malls

🎤 Concerts

🏭 Industrial Safety

🚦 Smart City Surveillance

---

# 🚀 Future Improvements

- Multi-Camera Support
- Cloud Dashboard
- Face Recognition
- Audio Alarm
- Database Logging
- Web Dashboard
- AI Crowd Prediction
- Mobile App Integration

---

# 🤝 Contributing

Contributions are welcome!

Fork the repository.

Create your feature branch.

Commit your changes.

Push to your branch.

Open a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

<div align="center">

Made with ❤️ using Python, YOLOv8 and OpenCV

⭐ Star this repository if you found it useful!

</div>
