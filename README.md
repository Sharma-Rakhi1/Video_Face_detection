# Video Face Detection Using Python

## Overview
This project implements face detection in a video using Python's OpenCV library. It processes a video file to identify human faces, highlights them with bounding boxes, and saves the annotated video as the output.

## Features
- Uses Haar Cascade classifier for face detection.
- Processes each frame of a video and detects faces.
- Annotates detected faces with bounding boxes.
- Saves the annotated video in the specified format.
- Optionally displays the video during processing.

## Requirements
To run this project, you need the following:
- Python 3.x
- OpenCV library (`cv2`)
- A pre-trained Haar Cascade file for frontal face detection (`haarcascade_frontalface_default.xml`)
- A video file for input

## Provided Resources
This project includes the following resources:
- **[Sample Input Video](https://github.com/Sharma-Rakhi1/Video_Face_detection/blob/main/Input.mp4)**: A test video file to use as input for the script.
- **[Haar Cascade File](https://github.com/Sharma-Rakhi1/Video_Face_detection/blob/main/haarcascade_frontalface_default.xml)**: The `haarcascade_frontalface_default.xml` file required for face detection.

## Installation
1. Install Python from [python.org](https://www.python.org/).
2. Install OpenCV by running:
   ```bash
   pip install opencv-python
