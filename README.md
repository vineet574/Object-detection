# Object-detection
This project implements a real-time object detection system using Python, OpenCV, and a pre-trained MobileNetSSD model. The system captures live video from a webcam, processes each frame, and detects common objects like people, cars, and animals, displaying bounding boxes and confidence scores around detected objects in real time.
# AI-Powered Real-Time Object Detection System

This project demonstrates a real-time object detection system using Python, OpenCV, and a pre-trained MobileNetSSD model. The system uses your webcam feed to detect objects and displays bounding boxes along with confidence levels around the detected objects.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [How to Run](#how-to-run)
- [License](#license)

## Features
- Real-time object detection using your webcam.
- Displays bounding boxes and confidence percentages for detected objects.
- Uses a pre-trained MobileNetSSD model.

## Requirements
- Python 3.x
- Libraries:
  - OpenCV
  - TensorFlow
  - Numpy

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name
Install the required dependencies: Use the following command to install the required Python libraries:

pip install opencv-python tensorflow numpy

Download the pre-trained model files: You need two files:

deploy.prototxt: Download here
mobilenet_iter_73000.caffemodel: Download here
Place both files in the project directory.

How to Run
Run the object detection script: Make sure you're in the project directory and run the following command:

python object_detection.py

Using the system:

The script will start your webcam and begin detecting objects in real-time.
Press q to stop the program

### Steps to Follow:
1. Copy and paste the above content into a `README.md` file.
2. Create a new repository on GitHub.
3. Upload your project files, including the `README.md`, your Python script, and the model files.
4. Push everything to your GitHub repository.

