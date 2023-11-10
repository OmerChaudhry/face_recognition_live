# Live Face Recognition using DeepFace and OpenCV

## Overview

This Python project leverages DeepFace, an advanced face recognition library, and OpenCV to perform real-time face recognition using a webcam. The system compares detected faces against a reference image for identification and verification.

## Installation

### Prerequisites

- **Python 3.x**
- **OpenCV:** Install using `pip install opencv-python-headless`
- **DeepFace:** Install using `pip install deepface`

### Setup

1. **Reference Image:** Place your reference image as `reference.jpg` in the project directory. This image will be utilized for face comparison during live detection.

2. **Webcam Configuration:** The script is set to use the default webcam (index 0). Adjust the index as needed in `cv2.VideoCapture()` if you have multiple cameras.

## Execution

Run the script `live_face_recognition.py` using Python.

```bash
python live_face_recognition.py
