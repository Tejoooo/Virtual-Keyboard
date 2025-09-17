# Gesture Keyboard Search

This project is a gesture-based virtual keyboard that allows users to type using hand gestures and search queries on Google, YouTube, or Instagram.

## Features

- Finger gesture detection using MediaPipe
- Virtual keyboard with clickable buttons via gesture tap
- Platform selector (Google, YouTube, Instagram)
- Submit query with gesture-based button press

## Installation

```bash
pip install opencv-python mediapipe numpy
```

## Usage

```bash
python main.py
```

Press `q` to exit the application.

## File Structure

- `main.py`: Main app logic.
- `ui/`: Button, keyboard, and platform UI logic.
- `utils/`: Hand tracking and search logic.

## Notes

Ensure your webcam is connected and working. This app opens the webcam to detect hand gestures.
Virtual Gesture keypad
