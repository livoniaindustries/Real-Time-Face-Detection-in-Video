# Real-Time Face Detection in Video

This project uses OpenCV's deep learning module to perform real-time face detection using a pre-trained Caffe model.

---

## Features
- Detect faces from a webcam video stream.
- Display bounding boxes around detected faces.
- Show the confidence score for each detection.
- Filter out weak detections based on a configurable confidence threshold.

---

## Requirements

- Python 3.x
- OpenCV
- NumPy
- imutils

---

## Installation

1. Create a virtual environment and activate it:

```bash
python -m venv venv
```
On Windows
```
venv\Scripts\activate
```
On macOS/Linux
```
source venv/bin/activate
```
Install the required Python packages:
```
pip install opencv-python numpy imutils

```
Usage
```

python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
