# OpenCV Image Processing Scripts

## Overview
This repository contains two Python scripts demonstrating basic image processing techniques using OpenCV. The scripts are designed to showcase color-based object detection and masking in real-time video feeds.

## Script Descriptions

### 1. Screen Capture and Masking (`hsv filter screen.py`)
- This script captures a specific area of the screen and applies color-based masking to detect objects of a specified color.
- Features include:
  - Real-time screen capture.
  - HSV color space conversion.
  - Color range detection with trackbars for real-time adjustments.
  - Morphological operations to enhance the mask.
  - Bitwise operations to isolate the detected color.

### 2. Webcam Capture and Masking (`hsv filter camera.py`)
- Similar to the first script, this one uses a webcam feed instead of screen capture.
- It also demonstrates real-time color-based object detection with adjustable parameters.
- Features include:
  - Real-time video capture from the webcam.
  - HSV color space conversion and masking.
  - Trackbars for dynamic color range adjustments.
  - Application of morphological operations and bitwise masking.

## Prerequisites
- Python 3.x
- OpenCV library (`cv2`)
- Numpy library
- MSS library (for screen capture in `script1.py`)

## Usage

1. **Clone the Repository:**
git clone https://github.com/BoranCanOzel/OpenCV-HSV-Filtering.git
2. **Install Dependencies:**
3. pip install opencv-python numpy mss


3. **Run the Scripts:**
- For screen capture and masking:
  ```
  python hsv filter screen.py
  ```
- For webcam capture and masking:
  ```
  python hsv filter camera.py
  ```

4. **Adjust Parameters:**
- Use the trackbars in the 'marking' window to adjust the HSV color range for object detection.

5. **Exit the Program:**
- Press 'q' to close the windows and terminate the script.

## Note
These scripts are basic demonstrations for educational purposes and may require modifications for specific use cases.
