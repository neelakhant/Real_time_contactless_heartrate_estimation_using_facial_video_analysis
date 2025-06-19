# 💓 Real-Time Contactless Heart Rate Estimation Using Facial Video Analysis

> **Major Project** submitted by  
> **P. Neelakhant, P. Yogendra, T. Karthik, T.Ganesh**  
> B.Tech Artificial Intelligence  
> Vidya Jyothi Institute of Technology, Hyderabad  
> Under the guidance of **Mrs. K. Santhi Priya**

---

## 📌 Project Description

This project implements a **real-time, contactless heart rate monitoring system** using a standard webcam and facial video analysis.

By leveraging computer vision and signal processing techniques, the system detects facial landmarks, extracts physiological signals from skin tone changes, and estimates **heart rate in Beats Per Minute (BPM)** — **without any physical contact** or dedicated hardware like ECG or pulse sensors.

---

## 🧠 Key Technologies Used

- **Python**
- **OpenCV** – for video capture and processing
- **MediaPipe** – for face detection
- **Tkinter** – for GUI interface
- **NumPy / SciPy** – for signal analysis and peak detection
- **Matplotlib** – for real-time graph plotting

---

## ⚙️ Features

- Contactless, real-time heart rate estimation
- ROI (forehead) extraction using face landmarks
- Signal extraction from **HSV Saturation channel**
- Peak detection via FFT-based logic
- GUI with:
  - Live camera feed
  - Real-time BPM display
  - Heart rate signal graph

---

## 🔬 Validation

- Compared system BPM values with:
  - **Mi Band 5**
  - **Fire-Boltt Ninja**
  - **Apple Watch SE**
- Achieved consistent BPM readings within **±2 BPM** under normal lighting.

---

## 🧪 How It Works

1. Webcam captures live facial video.
2. Forehead region is identified using MediaPipe.
3. Color signal is extracted from **HSV Saturation**.
4. Signal is filtered and analyzed for peaks.
5. BPM is calculated and displayed with graph.

---

