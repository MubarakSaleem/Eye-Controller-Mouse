# Eye-Controller-Mouse
An innovative hands-free mouse controller powered by eye movements, built using Python, OpenCV, MediaPipe, and PyAutoGUI. This project enables users to control their computer cursor using their eyes, providing an accessible solution for individuals with limited mobility
![download](https://github.com/user-attachments/assets/d93bd69b-209c-4682-99f5-157db204a5bb)
![download (1)](https://github.com/user-attachments/assets/f837b5d9-2483-48dc-af14-7f421a4918a8)

# Features

  1)Real-time Eye Tracking: Utilizes OpenCV and MediaPipe to detect and track eye movements in real-time.

  2)Cursor Control: Maps eye movements to mouse cursor movements using PyAutoGUI.
 
  3)Click Gestures: Supports left-click and right-click actions through predefined eye gestures (e.g., blinking or prolonged gaze).

  4)Customizable Sensitivity: Adjustable parameters for cursor speed and gesture detection thresholds.

  5)Cross-Platform: Works on Windows, macOS, and Linux.

# Technologies Used
OpenCV: For real-time video processing and eye detection.

MediaPipe: For facial landmark detection and eye tracking.

PyAutoGUI: For simulating mouse movements and clicks.

Python: The core programming language for the project.

# Installation
Prerequisites
Python 3.7 or higher

Webcam

Steps
Clone the repository:

bash

git clone https://github.com/MubarakSaleem/Eye-Controller-Mouse.git
cd Eye-Controller-Mouse
Install the required dependencies:

bash
pip install -r requirements.txt
  opencv-python==4.7.0.72
  mediapipe==0.10.0
  pyautogui==0.9.54
  numpy==1.24.3

# Usage
Calibration: Follow the on-screen instructions to calibrate the eye tracking system.

Cursor Movement: Move your eyes to control the mouse cursor.

Click Gestures:

Left Click: Blink once or perform a specific gesture (e.g., prolonged gaze).

Right Click: Blink twice or perform another predefined gesture.

Exit: Press Q to quit the application.

# Acknowledgments## Acknowledgments

[MediaPipe](https://mediapipe.dev/) for the face mesh model.

[OpenCV](https://opencv.dev/) for real-time image processing.

[PyAutoGUI](https://pyautogui.dev/) for mouse control

Inspired by accessibility projects that aim to improve the lives of individuals with disabilities.
