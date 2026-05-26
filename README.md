# Backend-Flask Project
## Description
The Backend-Flask project is a real-time object detection system using YOLO (You Only Look Once) algorithm. It detects objects in a video stream and sends the detection results to the client in real-time.
## Key Features
- Real-time object detection using YOLO
- Supports detection of persons, cars, motorcycles, and buses
- Converts image coordinates to world coordinates using homography matrix
- Sends detection results to the client in real-time using Server-Sent Events (SSE)
## Tech Stack
- Python 3.x
- Flask
- OpenCV
- PyTorch
- Ultralytics YOLO
## Installation
To install the required dependencies, run the following command:
```npm
pip install -r requirements.txt
```
## Usage
1. Run the Flask application using `python app.py`
2. Open a web browser and navigate to `http://localhost:5000`
3. The detection results will be displayed in real-time on the web page
## Environment Variables
- `VIDEO_PATH`: the path to the video file
- `MODEL_PATH`: the path to the YOLO model file
- `TARGET_CLASSES`: the classes to detect (e.g. person, car, motorcycle, bus)
## Example Use Case
- Detecting objects in a surveillance video stream
- Tracking objects in a real-time video feed
- Analyzing object detection results for security or analytics purposes