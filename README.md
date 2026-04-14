# ✋ AI Media Controller using Hand Gestures 🎵

## 🚀 Project Overview
This project is a **Real-Time Media Controller** that allows users to control media playback using hand gestures without touching any device. It uses computer vision techniques to detect hand movements and map them to actions like Play/Pause.


## 🧠 Features
- ✋ Real-time hand detection using webcam  
- 🔢 Finger counting using hand landmarks  
- 🎵 Play/Pause control using gestures  
- ⚡ Fast and lightweight system  
- 🖥️ Works with YouTube, VLC, and other media players  

---

## 🛠️ Technologies Used
- Python  
- OpenCV  
- MediaPipe  
- PyAutoGUI  

---

## ⚙️ How It Works
1. Webcam captures live video  
2. MediaPipe detects hand landmarks (21 key points)  
3. Finger positions are analyzed  
4. Gestures are identified  
5. Actions are sent using PyAutoGUI  

---

## 🎮 Gesture Controls

| Gesture | Action |
|--------|--------|
| ✋ Open Hand (5 fingers) | Play / Pause |
| ✊ Fist (0 fingers) | Play / Pause |

---

## 🧑‍💻 Installation

```bash
pip install opencv-python mediapipe pyautogui
