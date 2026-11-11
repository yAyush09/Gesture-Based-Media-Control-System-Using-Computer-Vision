
# Hand Gesture Based Media Control System

## Project Overview

This project is a Python-based computer vision application that allows users to control media playback using hand gestures in real time through a webcam.

It uses MediaPipe to detect hand landmarks, OpenCV for image processing, and PyAutoGUI to execute keyboard commands based on recognized gestures.

## Features

- Real-time hand detection using webcam
- Finger counting and gesture recognition
- Media playback control through hand gestures
- Automatic keyboard command execution
- Single-hand tracking
- Real-time hand landmark visualization

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI

## Gesture Controls

| Number of Fingers | Keyboard Action | Function |
|---|---|---|
| 1 Finger | Right Arrow | Forward |
| 2 Fingers | Left Arrow | Backward |
| 3 Fingers | Up Arrow | Volume Up |
| 4 Fingers | Down Arrow | Volume Down |
| 5 Fingers | Space | Play / Pause |

## Installation

Clone the repository:

```bash
git clone https://github.com/yAyush09/Media-Control-Using-Hand-Gestures.git
```

Navigate to the project folder:

```bash
cd Media-Control-Using-Hand-Gestures
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## How to Run

Execute the following command:

```bash
python main.py
```

Make sure your webcam is connected and accessible.

Press ESC to exit the application.

## How It Works

1. OpenCV captures live video from the webcam.
2. MediaPipe detects hand landmarks.
3. The program counts raised fingers.
4. Each recognized gesture is mapped to a keyboard command.
5. PyAutoGUI executes the corresponding keyboard action.

## Project Output

The application displays real-time hand landmarks and connections on the webcam feed.

## Requirements

- Python 3.12
- Working webcam
- Windows or compatible environment

## Original Project Credit

Original repository:
https://github.com/sg-0x/Media-contol-using-gestures

Original MIT License retained.
