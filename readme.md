# Face Detection with OpenCV

## Overview

This project demonstrates **real-time face detection** using the **Haar Cascade Classifier** or the **Dlib** library, both of which are commonly used for face detection tasks. The application can detect faces in an image or video stream (e.g., webcam) and draw bounding boxes around them.

In this project, we'll use the **Haar Cascade Classifier**, which is a fast and efficient method for detecting faces in images and video streams.

## Features

- Detect faces in real-time from a webcam video stream.
- Draw bounding boxes around detected faces.
- Handle both image and video-based face detection.
- Option to save output images with detected faces.

## Requirements

- **Python** 3.x
- **OpenCV** 4.x
- **Numpy** (Optional but recommended for image manipulation)

## Installation

### Step 1: Clone the Repository

Clone the repository to your local machine.

```bash
git clone https://github.com/DEVang0876/face-detection.git
cd face-detection
```



### Step 2: Set up the Python Environment

It’s recommended to use a** ****virtual environment** for this project to manage dependencies.



python3 -m venv face_detection_env
source face_detection_env/bin/activate  # On macOS/Linux


### Step 3: Install Dependencies

Install the required libraries using** **`pip`.

pip install opencv-python numpy



## Usage

### Step 1: Run the Script

Execute the Python script to start face detection using the photo.

The program will open a window displaying image feed, and it will automatically detect faces in real-time.


python face_detection.py  
(Run .py file)
