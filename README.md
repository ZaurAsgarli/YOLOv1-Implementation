YOLOv1 From Scratch (TensorFlow)

This repository contains a Jupyter Notebook that implements YOLOv1 (You Only Look Once) from the ground up in TensorFlow. The project walks through dataset preparation, network architecture creation, custom loss function design, and object detection evaluation.

Features
Complete YOLOv1 architecture implemented manually in TensorFlow

Custom dataset loading and preprocessing

YOLO-specific loss function including coordinate, confidence, and class prediction terms

Training loop with optimizer, learning rate scheduling, and batch processing

Inference stage for detecting bounding boxes in images

Installation
Required Python packages:

TensorFlow

NumPy

Pandas

Matplotlib

Seaborn

tqdm

OpenCV (optional for image handling)

Usage
Open YoloV1FromScratch.ipynb

Prepare and load your dataset (Pascal VOC or similar)

Train the model using the provided training pipeline

Run inference on test images to visualize bounding box predictions

Dataset
The notebook supports Pascal VOC-style datasets but can be adapted for COCO or custom datasets with minimal changes.

Output
The notebook produces:

Training and validation loss curves

Bounding box predictions on sample images

Performance metrics such as mAP (mean Average Precision)

