# Drowsiness Detection System

## Introduction
Our Project employs facial landmarks and the eye aspect ratio to detect drowsiness in real-time using a webcam feed. It utilizes the dlib library for face detection and shape prediction, along with essential libraries such as OpenCV, imutils, and pygame for audio alerts.

## Libraries Used
- scipy.spatial.distance: Computes the Euclidean distance.
- imutils.face_utils: Provides facial landmark indices.
- imutils: Offers convenience functions for OpenCV.
- dlib: A toolkit for machine learning and computer vision.
- pygame: Used for playing an audio alert when drowsiness is detected.
- cv2: OpenCV library for computer vision.

## Features
- Real-time drowsiness detection using facial landmarks.
- Audio alert using pygame when drowsiness is detected.
- Saves a screenshot with a timestamp to a specified folder during an alert.

## How to Run

1. Create a virtual environment (optional but recommended):

 ```bash
 python -m venv venv
 ```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

Start the development server:
```bash
python Drowsiness_Detection.py
```

Stay alert and drive safely!