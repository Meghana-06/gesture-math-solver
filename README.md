# Gesture Math Solver 🖐➕➗

A Python-based computer vision project that allows users to solve mathematical expressions using **hand gestures** and a **webcam**. This project uses **OpenCV**, **MediaPipe**, and **NumPy** to detect and recognize finger positions and interpret them as numbers and mathematical operators.

---

## 🚀 Features

- ✋ Real-time hand gesture detection using webcam
- ➕➖ Recognition of numbers and math operators
- 🧠 Math expression building and live evaluation
- 💻 Simple and interactive UI via OpenCV

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **MediaPipe**
- **NumPy**

---

## 📦 Requirements

Make sure you have Python installed, then install the required libraries:

```bash
pip install opencv-python mediapipe numpy

## 🧠 How It Works
The webcam captures real-time video.

MediaPipe identifies hand landmarks.

A custom logic maps the number of extended fingers to numbers (e.g., 1 finger = 1, 5 fingers = 5).

Math expressions are built live and evaluated when triggered (e.g., by a gesture or key).
