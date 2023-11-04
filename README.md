Face Detection with OpenCV

This repository contains a Python script that uses the OpenCV library to perform real-time face detection using a pre-trained Haar Cascade Classifier. The script captures video from a webcam, processes each frame to detect faces, and outlines the detected faces with green rectangles.

## Getting Started

To run the face detection script, you need to have Python and OpenCV installed on your system.

### Prerequisites

- Python (>=3.6)
- OpenCV

You can install OpenCV using pip:

pip install opencv-python

Usage

    Clone this repository to your local machine:

python face_detection.py

    The script will open a window displaying the video feed from your webcam. It will detect and outline faces in real-time.

    Press the 'Esc' key to exit the program.

Customization

You can customize the code by modifying the Haar Cascade Classifier used for face detection or by adjusting the detection parameters (e.g., scaling factor and minimum neighbors) in the script.

Acknowledgments

    The face detection is performed using OpenCV's Haar Cascade Classifier for frontal face detection.
