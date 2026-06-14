# finger-counter-using-opencv-and-mediapipe
A real-time finger counting system using OpenCV and MediaPipe that detects hand landmarks through a webcam and counts the number of raised fingers, enabling accurate gesture recognition for human-computer interaction applications.

## Features
- Real-time hand tracking using webcam
- Detection of 21 hand landmarks
- Accurate finger counting system
- Works for both left and right hand
- Live video feed with visual feedback

## How It Works
The system uses MediaPipe to detect 21 key points on a hand. By analyzing the positions of finger tip landmarks relative to lower joints, it determines which fingers are raised and calculates the total number of extended fingers in real time.

## Technologies Used
- Python
- OpenCV
- MediaPipe
- NumPy

## Installation
```bash
pip install opencv-python mediapipe numpy
