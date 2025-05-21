# Driver Drowsiness, Distraction, and Gaze Detection System

This project uses **MediaPipe**, **OpenCV**, and **Python** to monitor a driver's alertness in real-time using a webcam. It detects:
- Drowsiness (via Eye Aspect Ratio)
- Distraction (via Head Pose Estimation)
- Gaze direction (via Iris tracking)

## 🔧 Tech Used
- Python
- OpenCV
- MediaPipe
- NumPy

## 💡 How It Works
- Uses face landmarks to estimate eye closure (EAR)
- Uses iris position to detect gaze direction
- Estimates yaw angle to flag distraction
- Works in real-time from webcam

## 🛠 Installation
Install required packages:
```bash
pip install mediapipe opencv-python numpy
