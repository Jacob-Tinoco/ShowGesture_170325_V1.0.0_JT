# 🖋️ ShowGesture_170325_V1.0.0_JT

  > Version: V1.2.0  
  > Creation Date: 13-03-2025  
  > Script: GestureRecognitionV1.2.0_JT
> 
  > Estado: Funcional con pruebas exitosas en entorno local
---

## 📘 General Description
A real-time hand gesture recognition system using computer vision that detects and classifies 13 different hand gestures with confidence metrics. The system processes video input through a webcam and provides visual feedback of detected gestures, finger positions, and confidence levels.

---

## 📚 Table of Contents
1. [General Description](#-general-description)
2. [Project Structure](#-project-structure)
3. [Key Scripts Description](#-key-scripts-description)
4. [How to Run](#-how-to-run)
5. [Dataset / Testing](#-dataset--testing)
6. [Technologies Used](#-technologies-used)
7. [Final Notes](#-final-notes)
8. [Author](#-author)

---

## 📁 Project Structure
```bash
hand-gesture-recognition/
├── GestureRecognitionV1.2.0_JT.py    # Main script
├── requirements.txt                    # Dependencies
└── README.md                          # This document
```

---

## 📜 Key Scripts Description
### GestureRecognitionV1.2.0_JT.py
- **Author**: Jacob Tinoco
- **Function**: Main script for real-time hand gesture recognition
- **Last Modified**: 13-03-2025
- **Status**: Production
- **Features**:
  - Real-time hand tracking
  - 13 different gesture recognitions
  - Confidence metrics for each finger
  - Mirror mode display
  - Bilateral hand detection support

---

## 🚀 How to Run
1. Install dependencies:
```bash
pip install opencv-python mediapipe
```

2. Run the main script:
```bash
python GestureRecognitionV1.2.0_JT.py
```

3. Use ESC key to exit the program

---

## 🧪 Dataset / Testing
### Input
- Real-time video feed from webcam
- Supports both left and right hand detection

### Output
- Visual display showing:
  - Hand landmarks
  - Finger status (extended/closed)
  - Detected gesture
  - Confidence percentages for each finger
  - Mirror mode display

### Supported Gestures
1. Thumbingcito
2. Indication
3. Don't be rude
4. Annular extension
5. Pinky
6. Looser
7. Love and Peace
8. Punk Sign
9. Rock and roll
10. Index, middle and ring
11. Thumb extension
12. Hello World
13. Close

---

## 📦 Technologies Used
- Python 3.11
- OpenCV (cv2)
- MediaPipe
- Math library

---

## 📝 Final Notes
### Performance Metrics
- Minimum confidence threshold: 85% for fingers 1,2,3,4
- Minimum confidence threshold: 15% for thumb
- Real-time processing capability

### Known Limitations
- Spanish character encoding issues (ñ, accents)
- Gesture detection and finger counting overlap in upper screen margin

### Best Practices
- Ensure good lighting conditions
- Keep hands within camera frame
- Maintain appropriate distance from camera

---

## ✍️ Author
JT  
Last Updated: 27-04-2025  
