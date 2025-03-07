# Face Detection, Age, and Gender Prediction

This project uses OpenCV's deep learning module to detect faces and predict age & gender in a video stream.

## Requirements
- Python 3.x
- OpenCV
- NumPy

Install dependencies:
```sh
pip install opencv-python numpy
```

## Usage
Ensure the following model files are in the project directory:
- `opencv_face_detector.pbtxt`, `opencv_face_detector_uint8.pb`
- `age_deploy.prototxt`, `age_net.caffemodel`
- `gender_deploy.prototxt`, `gender_net.caffemodel`


## Features
- Detects faces from webcam feed.
- Predicts age & gender.
- Saves output as `output.avi`.
- Press `q` to exit.



