# Emotion Detection Project

## Overview
This project detects human facial emotions in images using Python, OpenCV, and the FER (Facial Expression Recognition) library. It identifies faces, classifies their emotions, and displays corresponding emojis. This can be useful for applications in psychology, marketing, human-computer interaction, and more.

## Features
- Face detection using OpenCV Haar cascades
- Emotion recognition using the FER library
- Visualization of detected emotions with emojis and confidence scores
- Works on static images (can be extended to video/webcam)

## Installation
Make sure you have Python installed (version 3.6+ recommended).  
Install required packages using pip:

```bash
pip install opencv-python fer matplotlib

Usage

Upload an image containing human faces.
Run the Python script or Jupyter notebook.
The program will detect faces and display the detected emotions with emojis and confidence percentages.
Code Structure

emotion_detector.py (or .ipynb): Main script/notebook that runs face and emotion detection.
haarcascade_frontalface_default.xml: Pretrained face detection model used by OpenCV (comes bundled with OpenCV).
Other resource files (if any).
Known Issues / Limitations

Emotion detection accuracy depends on image quality and face visibility.
May not perform well with occluded or side-profile faces.
Currently supports only static images; live webcam support requires additional setup.
Future Work

Add live webcam emotion detection.
Support video file input.
Improve UI for better visualization.
Experiment with different emotion recognition models.
Credits

FER library
OpenCV community and Haar cascades
Inspiration from computer vision tutorials
License

This project is licensed under the MIT License. See the LICENSE file for details.

