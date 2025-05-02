# Hand-Recognition

This project implements real-time hand tracking and gesture recognition using [MediaPipe](https://google.github.io/mediapipe/) and OpenCV.
It was originally based on [this tutorial video](https://www.youtube.com/watch?v=vQZ4IvB07ec) by Nicholas Renotte.

## 🔧 Installation

To install all required dependencies, run:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

* `hand_tracking_min_code.py`
  Tracks and visualizes hand landmarks in a real-time webcam feed.

* `hand_tracking_two_fingers_touch.py`
  Detects when the thumb and index finger are touching and prints `True` when they do
