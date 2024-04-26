# Python OpenCV Car Steering Control System

## Overview

This Python application implements a car steering control system using OpenCV for color detection and contour tracking. The system allows users to control the car's movement using hand gestures captured by a webcam. Hand gestures for turning left, turning right, and activating nitro are detected and mapped to corresponding keyboard inputs for controlling the car in a gaming environment.

## Features

- **Color Detection**: Detects specific colors (e.g., green) using OpenCV's HSV color space.
- **Contour Tracking**: Tracks contours of detected colors to identify hand gestures.
- **Steering Control**: Maps hand gestures to keyboard inputs for controlling the car's movement.
- **Nitro Activation**: Activates nitro boost using a specific hand gesture.

## How to Use

1. **Setup Environment**: Ensure you have Python installed along with necessary libraries (`numpy`, `cv2`, `imutils`, `directkeys`).
   
2. **Run the Code**: Execute the `steering.py` script to start the application. Ensure your webcam is connected and positioned correctly.
   
3. **Hand Gesture Control**: Use hand gestures in front of the webcam to control the car. Move your hand left to turn left, right to turn right, and perform a specific gesture to activate nitro.

## File Structure

- `steering.py`: Main Python script that implements the car steering control system using OpenCV.
- `color.py`: Python script for color detection and contour tracking using OpenCV.
- `directkeys.py`: Python script defining functions for simulating keyboard inputs using ctypes.

## Dependencies

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)
- Imutils (`imutils`)

## Contributing

Contributions are welcome! If you find any bugs or want to suggest enhancements, please open an issue or submit a pull request.

