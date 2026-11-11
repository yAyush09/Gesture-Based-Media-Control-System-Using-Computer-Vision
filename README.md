
# Media Control Using Hand Gestures

## Project Overview
A Python-based computer vision project that allows users to control media playback using hand gestures through a webcam.

## Features
- Real-time hand detection
- Finger counting using hand landmarks
- Media playback control using gestures
- Webcam-based interaction

## Technologies Used
- Python
- OpenCV
- MediaPipe
- PyAutoGUI

## Gesture Controls

| Fingers Detected | Action |
|---|---|
| 1 Finger | Forward |
| 2 Fingers | Backward |
| 3 Fingers | Volume Up |
| 4 Fingers | Volume Down |
| 5 Fingers | Play / Pause |

## Installation

Install the required libraries:

```bash
pip install opencv-python mediapipe pyautogui
```

## How to Run

```bash
python main.py
```

Make sure your webcam is connected.

## Original Project Credit

Original repository: https://github.com/sg-0x/Media-contol-using-gestures

This repository retains the original MIT license.
