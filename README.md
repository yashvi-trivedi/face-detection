# Face Detection with OpenCV

Real-time face detection using OpenCV: 

Captures video from your webcam and applies face detection to identify and highlight faces in the video stream with bounding boxes.

## Prerequisites

Before running this project, make sure you have the following installed:

- Python 3.x
- OpenCV (`cv2`)

To install OpenCV, run:

```bash
pip install opencv-python
```
## How It Works
1. Haar Cascade Classifier: The face detection is powered by OpenCV's Haar Cascade Classifier, a machine learning-based approach for object detection.

2. Webcam Capture: The webcam is accessed using OpenCV's cv2.VideoCapture() method.

3. Face Detection: For each frame captured from the webcam, the image is converted to grayscale, and the face detector (CascadeClassifier) identifies faces in the frame. Each detected face is marked with a green bounding box.

4. Real-Time Display: The processed video frame with bounding boxes is displayed in a separate window.

## How to Run
Clone this repository to your local machine
```bash
git clone https://github.com/your-username/face-detection-opencv.git
```

Navigate to the project directory:
```bash
cd face-detection-opencv
```

Install the dependencies
```bash
pip install -r requirements.txt
```

Run the Python script:
```bash
```python face_detection.py

A window will appear showing the webcam feed with green bounding boxes around detected faces. Press `q` to quit the program.
