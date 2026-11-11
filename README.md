# Hand Gesture Based Media Control System

## Project Overview
A Python-based computer vision application that allows users to control media playback using hand gestures in real time through a webcam.

The system detects hand landmarks and counts raised fingers to perform keyboard actions automatically.

## Features
- Real-time hand detection using webcam
- Finger counting and gesture recognition
- Media playback control using hand gestures
- Keyboard automation
- Single-hand gesture detection

## Technologies Used
- Python
- OpenCV
- MediaPipe
- PyAutoGUI

## Gesture Controls

| Hand Gesture | Keyboard Action |
|---|---|
| 1 Finger | Right Arrow |
| 2 Fingers | Left Arrow |
| 3 Fingers | Up Arrow |
| 4 Fingers | Down Arrow |
| 5 Fingers | Space |

## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## How to Run

```bash
python main.py
```

Allow webcam access and show hand gestures in front of the camera.

Press ESC to exit the application.

## How It Works
1. OpenCV captures live webcam frames.
2. MediaPipe detects hand landmarks.
3. The program counts raised fingers.
4. Each recognized gesture is mapped to a keyboard command.
5. PyAutoGUI executes the corresponding keyboard action.

## Original Project Credit

Original repository:
https://github.com/sg-0x/Media-contol-using-gestures

Original MIT License retained.
