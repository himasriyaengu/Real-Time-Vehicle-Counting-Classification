# 🚗 Real-Time Vehicle Counting and Classification

A computer vision-based traffic monitoring system that automatically detects, tracks, counts, and classifies vehicles from video streams using Python, OpenCV, and YOLO.

The system processes traffic videos in real time, identifies moving vehicles, tracks their movement through a defined Region of Interest (ROI), counts vehicles crossing a virtual counting line, and performs vehicle classification for traffic analytics and intelligent transportation applications.

---

## 📌 Features

✅ Real-time vehicle detection

✅ Vehicle tracking and counting

✅ Vehicle classification

✅ Traffic flow analysis

✅ Region of Interest (ROI) selection

✅ Video stream processing

✅ Bounding box visualization

✅ Transportation analytics support

---

## 🛠 Technologies Used

- Python
- OpenCV
- YOLO
- NumPy
- Computer Vision
- Image Processing

---

## 🔄 System Workflow

1. Input traffic video stream
2. Detect moving vehicles
3. Apply object tracking
4. Define Region of Interest (ROI)
5. Count vehicles crossing the virtual counting line
6. Classify detected vehicles
7. Generate traffic statistics and analytics

---

## 📂 Project Structure

```text
├── inputVideos/          # Input traffic videos
├── outputVideos/         # Processed output videos
├── yolo/                 # YOLO configuration and weights
├── main.py               # Main application
├── runDetections.py      # Detection module
├── yolo_video.py         # YOLO processing
├── Gui.py                # GUI interface
├── requirements.txt      # Dependencies
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/himasriyaengu/Real-Time-Vehicle-Counting-Classification.git
cd Real-Time-Vehicle-Counting-Classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

```bash
python main.py
```

or

```bash
python runDetections.py
```

---

## 📊 Applications

- Smart Traffic Management
- Intelligent Transportation Systems
- Traffic Density Monitoring
- Vehicle Flow Analysis
- Urban Mobility Analytics
- Transportation Research

---

## 📈 Key Learning Outcomes

- Object Detection using YOLO
- Vehicle Tracking Techniques
- Computer Vision Pipeline Development
- Video Processing with OpenCV
- Traffic Analytics Systems
- Real-Time Monitoring Applications

---

## 🎓 Academic Relevance

This project demonstrates practical implementation of:

- Computer Vision
- Machine Learning
- Image Processing
- Intelligent Transportation Systems
- Real-Time Analytics

---

## 👩‍💻 Author

**Himasriya Engu**

M.S. Computer Science

University of Central Florida

LinkedIn: https://linkedin.com/in/himasriya-engu

Portfolio: https://himasriyaengu.github.io

---

## ⭐ Future Improvements

- Live camera stream support
- Vehicle speed estimation
- Lane-wise vehicle analytics
- Night-time vehicle detection
- Deep learning-based vehicle classification
- Dashboard integration using Power BI
