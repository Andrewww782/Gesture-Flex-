# Gesture-Flex-
This project employs computer vision to enable gesture-based adjustments of screen brightness and system volume. By tracking hand movements via webcam, users can intuitively control display brightness and audio volume.
Gesture-Controlled Brightness & Volume
This Python project utilizes computer vision techniques to enable gesture-based control of screen brightness and system volume. By leveraging the Mediapipe library for hand tracking and OpenCV for image processing, the program detects hand gestures in real-time from the webcam feed. Left hand gestures control screen brightness, while right hand gestures adjust system volume.

Features:
Gesture Recognition: Detects left and right hand gestures separately.
Brightness Control: Adjust screen brightness by moving the left hand vertically.
Volume Control: Control system volume with right hand movements.
Real-Time Visualization: Overlay of hand gestures on the webcam feed using OpenCV drawing utilities.

Requirements:
Python 3.x
OpenCV
Mediapipe
Pycaw
Screen_brightness_control

Usage:
Install the required libraries using pip install -r requirements.txt.
Run the gesture_control.py script.
Use left hand gestures for brightness and right hand gestures for volume control.
To exit, press 'q' on the keyboard.
