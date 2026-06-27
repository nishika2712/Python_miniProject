# Real-Time Face Detection using OpenCV

A Python script demonstrating real-time face detection from a live 
webcam feed using OpenCV's Haar Cascade classifier.

## What it does

Captures live video from the webcam, converts each frame to grayscale, 
and uses a pretrained Haar Cascade model to detect faces, drawing a 
bounding box around each detected face in real time.

## Tech Used

- Python
- OpenCV (`cv2`)
- Haar Cascade Classifier (pretrained, frontal face detection)

## How to Run

1. Install dependencies:
```bash
   pip install opencv-python
```
2. Download `haarcascade_frontalface_default.xml` from OpenCV's GitHub 
   repository and place it in the same directory.
3. Run the script:
```bash
   python face_detection.py
```
4. Press `Esc` to exit the webcam window.

## Context

This was an early exploration into computer vision fundamentals using 
a pretrained model, done as part of my foundational learning in Python 
before moving into deeper AI/ML work with Salesforce Agentforce and 
Einstein AI.
