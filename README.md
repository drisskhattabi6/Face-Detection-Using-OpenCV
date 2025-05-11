# Face Detection Using OpenCV

This project demonstrates real-time face detection using OpenCV and a webcam. It uses Haar cascade classifiers to detect faces in each frame captured from the webcam and draws a bounding box around them.

## Features

* Real-time face detection using a webcam
* Uses Haar Cascade Classifier provided by OpenCV
* Draws green rectangles around detected faces

## Requirements

* Python 3.x
* OpenCV

You can install OpenCV using pip:

```bash
pip install opencv-python opencv_contrib_python opencv_python_headless

```

## How It Works

1. Loads the Haar Cascade face detection model from OpenCV.
2. Captures video from the default webcam.
3. Converts each frame to grayscale.
4. Detects faces in the frame.
5. Draws a rectangle around each detected face.
6. Displays the video with detected faces until the user presses `q` to quit.

## Usage

Run the script:

```bash
python face_detection.py
```

To stop the webcam stream, press the **`q`** key.
