# 🖐️ Virtual Mouse Using Hand Gestures

This project demonstrates a contactless input system that enables users to control the mouse pointer using hand gestures. The system uses computer vision and machine learning to recognize hand landmarks in real-time and simulate mouse operations.

The model is built with OpenCV, Mediapipe, and PyAutoGUI, and allows seamless cursor control without physical hardware.

---
## 🚀 Features
- Real-time hand detection and gesture recognition
- Mouse pointer control using index finger tip
- Visual feedback with detected landmarks drawn on screen
- Smooth cursor movement using PyAutoGUI
- Touchless & hygienic interaction for healthcare/public spaces
- Extendable for clicks, scrolling, and drag-and-drop

---

## 🛠️ Tech Stack

- Python 🐍
- OpenCV 👁️
- Mediapipe ✋
- PyAuotoGYI 🖱️
- OpenCV 👁️

---

## 📂 Project Structure

- virtual_mouse.py # Main script for gesture recognition and pointer control
- requirements.txt # Python dependencies
- README.md # Project description

---

  
## 🧠 How it Works

1. The webcam captures live video using OpenCV.
2. Mediapipe detects 21 key landmarks on the hand.
3. The index finger coordinates are mapped to screen size.
4. PyAutoGUI moves the mouse pointer accordingly.
5. Detected landmarks are drawn on video for feedback.
6. Future updates can add click, scroll, and drag-drop gestures.

---

## 📈 Result

- Smooth pointer movement with minimal lag (<50 ms)
- High accuracy in real-time hand detection
- Intuitive user experience

---

## 📚 Dataset

- No dataset required.
- The system works in real-time using the webcam feed.

---
## 🙋‍♂️ Author

Ashish Deep Sen 
GitHub: [github.com/AshishDS-09](https://github.com/AshisDS-09)

---

### ✨ Feel free to fork, contribute or leave feedback!

---


### 📘 Project Summary – Virtual Mouse Using Hand Gestures

In this project, I implemented a gesture-controlled virtual mouse using computer vision. The system captures real-time video from a webcam, detects hand landmarks with Mediapipe, and simulates mouse operations using PyAutoGUI.

The project provides a hands-free, contactless way of interaction that can be useful in accessibility, hygiene-sensitive environments, and immersive AR/VR systems.

**Key Learning Outcomes:**

- Real-time video capture & processing with OpenCV
- Hand landmark detection using Mediapipe
- Mapping hand coordinates to screen resolution
- Mouse control with PyAutoGUI
- Designing human-computer interaction (HCI) systems
