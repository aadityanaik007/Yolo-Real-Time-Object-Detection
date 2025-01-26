# Real-Time Object Detection with YOLO

This project demonstrates real-time object detection using the YOLO (You Only Look Once) algorithm, leveraging OpenCV and a pre-trained YOLO model. It supports both video files and live webcam feeds for object detection.

## Features

- **Object Detection**: Detects multiple objects in real-time using YOLOv3-tiny.
- **Real-Time Performance**: Processes video frames efficiently with OpenCV's DNN module.
- **Confidence Filtering**: Filters detections based on confidence thresholds.
- **Visualization**: Displays detected objects with bounding boxes and labels on the video feed.
- **FPS Display**: Shows the frames-per-second (FPS) on the output video.

---

## Requirements

To run this project, you need to have the following installed:

- Python 3.7+
- OpenCV (version 4.x recommended)

---

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/real-time-object-detection-yolo.git](https://github.com/aadityanaik007/Yolo-Real-Time-Object-Detection.git)
   cd real-time-object-detection-yolo
   ```

## Download Files

    Download official yolov3.weights and place it under a folder called weight.
    Download official yolov3-tiny.weights and place it under a folder called weight.
    Download yolov3.cfg and place it under a folder called cfg.
    Download yolov3-tiny.cfg and place it under a folder called cfg.
