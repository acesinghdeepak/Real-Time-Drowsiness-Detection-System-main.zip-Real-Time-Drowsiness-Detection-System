# 💤 Real-Time Drowsiness Detection System

A Python-based project that uses computer vision and facial landmark detection to monitor signs of drowsiness in real-time using a webcam. If the user's eyes remain closed beyond a certain threshold, an alarm is triggered to alert them.

---

## 📌 Features

- Real-time webcam feed monitoring
- Detects eye aspect ratio (EAR) to determine drowsiness
- Audio alert when drowsiness is detected
- Lightweight and runs on local machines

---

## 🧰 Tech Stack

- **Programming Language:** Python
- **Libraries Used:** 
  - OpenCV
  - dlib
  - imutils
  - scipy
  - playsound

---

## 📷 Eye Aspect Ratio (EAR) Concept

The Eye Aspect Ratio (EAR) is used to detect if eyes are closed. When EAR falls below a certain threshold for a continuous number of frames, the system assumes drowsiness.

---

## 🚀 Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/drowsiness-detection.git
cd drowsiness-detection
