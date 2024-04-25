# 📸 OpenCV Image Processing Scripts

## 🌟 Overview
This repository contains two Python scripts demonstrating basic image processing techniques using OpenCV, focusing on color-based object detection and masking in real-time video feeds.

## 📝 Script Descriptions

### 1️⃣ Screen Capture and Masking (`hsv_filter_screen.py`)
- 🎯 Captures a specific area of the screen.
- 🎨 Applies color-based masking to detect objects of a specified color.
- 🛠️ Features:
  - Real-time screen capture.
  - Conversion to HSV color space.
  - Dynamic color range detection with adjustable trackbars.
  - Morphological operations to refine the mask.
  - Bitwise operations to isolate the detected color.

### 2️⃣ Webcam Capture and Masking (`hsv_filter_camera.py`)
- 📹 Utilizes a webcam feed for object detection.
- 🖌️ Similar features as the first script, adapted for webcam use.
- 🛠️ Features:
  - Real-time webcam video capture.
  - HSV masking and conversion.
  - Trackbars for real-time color adjustment.
  - Morphological and bitwise operations to enhance detection.

## 📦 Prerequisites
- Python 3.x
- OpenCV library (`cv2`)
- Numpy library
- MSS library (for screen capture in `hsv_filter_screen.py`)

## 🚀 Usage

1️⃣ **Clone the Repository:**
   `git clone https://github.com/BoranCanOzel/OpenCV-HSV-Filtering.git`

2️⃣ **Install Dependencies:**
   `pip install opencv-python numpy mss`

3️⃣ **Run the Scripts:**
   - Screen capture and masking:
     ```
     python hsv_filter_screen.py
     ```
   - Webcam capture and masking:
     ```
     python hsv_filter_camera.py
     ```

4️⃣ **Adjust Parameters:**
   - Use the trackbars in the 'masking' window to fine-tune the HSV color range for object detection.

5️⃣ **Exit the Program:**
   - Press 'q' to close the windows and terminate the script.

## 📝 Note
- These scripts are intended as basic demonstrations for educational purposes. Modifications may be needed for specific applications.
