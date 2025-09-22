# Gesture-Controlled Virtual Keyboard

A **real-time virtual keyboard** controlled by hand gestures using your webcam. Type by hovering your fingers over keys, tap to select, and pinch for space/enter. Optional voice-to-text allows dictating text inside the app.

---

## Features
- **Live camera input** for real-time hand tracking.
- Detects finger positions and gestures using **MediaPipe + OpenCV**.
- **Virtual keyboard GUI** highlights keys when hovered.
- Gesture typing:
  - Index finger tap → key press
  - Thumb + index pinch → space/enter
- Optional **voice-to-text** for dictation within the app.
- Optional voice feedback for typed keys.

---

## Tech Stack
- **Python 3.x**  
- Libraries: OpenCV, MediaPipe, cvzone, Pygame  
- Optional: pyttsx3 (voice feedback), SpeechRecognition (voice-to-text)

---

## Installation & Running
1. Install dependencies:
pip install opencv-python mediapipe cvzone pygame pyttsx3 SpeechRecognition

2. Run the app
python main.py
