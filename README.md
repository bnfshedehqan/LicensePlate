# Car License Plate Detection with YOLO

A computer vision project for detecting car license plates using YOLO object detection models in Google Colab.

This project explores license plate detection using YOLOv3 and YOLOv5, with the experiments implemented and executed in a Google Colab environment.

## Overview

License plate detection is an important computer vision task used in applications such as:

- Automatic Number Plate Recognition (ANPR)
- Intelligent transportation systems
- Traffic monitoring
- Parking management
- Vehicle identification

In this project, YOLO-based object detection models are used to locate license plates in vehicle images.

The project includes experiments with both YOLOv3 and YOLOv5 to understand and apply different versions of the YOLO object detection architecture.

## Models

### YOLOv3

YOLOv3 is used as one of the baseline object detection models for detecting license plates.

The model processes an input image and predicts bounding boxes around detected license plates.

### YOLOv5

YOLOv5 is also used for license plate detection and provides a more modern YOLO-based implementation with an efficient training and inference workflow.

The experiments are performed using Google Colab, making it possible to use GPU acceleration without requiring a local deep learning environment.

## Features

- 🚗 Car license plate detection
- 🎯 Bounding box detection using YOLO
- 🧠 YOLOv3 implementation
- ⚡ YOLOv5 implementation
- ☁️ Google Colab-based experiments
- 🖼️ Image-based object detection
- 📊 Model training and inference
- 🔍 Visualization of detected license plates

## Tech Stack

- Python
- YOLOv3
- YOLOv5
- PyTorch
- OpenCV
- Google Colab
- Jupyter Notebook

## Workflow

The general workflow of the project is:

```text
Input Images
     ↓
Dataset Preparation
     ↓
Image Annotation
     ↓
Data Preprocessing
     ↓
YOLOv3 / YOLOv5
     ↓
Model Training
     ↓
Model Inference
     ↓
License Plate Detection
     ↓
Bounding Box Visualization
