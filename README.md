[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/paraleash99/football-detection-tracking/blob/main/football_detection_tracking_yolov8.ipynb)
# Football Player and Ball Detection & Tracking using YOLOv8

A computer vision project for detecting and tracking football players and the ball in video using YOLOv8 and ByteTrack.

## Project Overview

This project uses a YOLOv8 object detection model trained on a football detection dataset to identify players and the ball in football footage. ByteTrack is then used to track detected objects across consecutive video frames.

## Features

- Football player and ball detection
- YOLOv8 model fine-tuning
- Object tracking using ByteTrack
- Video-based inference
- Bounding box and tracking ID visualization
- Ball trajectory visualization
- Model evaluation using detection metrics

## Technologies Used

- Python
- PyTorch
- Ultralytics YOLOv8
- OpenCV
- Roboflow
- ByteTrack
- Google Colab

## Project Workflow

```text
Football Dataset
       ↓
Roboflow Dataset Preparation
       ↓
YOLOv8 Model Training
       ↓
Model Evaluation
       ↓
Object Detection on Video
       ↓
ByteTrack Object Tracking
       ↓
Ball Trajectory Visualization
       ↓
Output Video
