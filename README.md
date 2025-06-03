# Football Analysis using YOLOv8 and Supervision

This project provides a football match analysis pipeline using computer vision techniques. It uses **YOLOv8** for player detection and tracking, and **Supervision** for post-processing and visualization. Player clustering is done using **K-Means** to differentiate teams based on jersey color.

## Features

- Player detection and tracking using YOLOv8
- Jersey color-based team classification via K-Means
- Frame-by-frame analysis of football match footage
- Real-time or video-based analytics pipeline
- Visualization of team clusters and tracking paths

Model Details
Model: YOLOv8n (can be swapped with yolov8s, yolov8m, etc.)

Clustering: KMeans on RGB mean values inside player bounding boxes

📦 Dependencies
Python 3.8+

Ultralytics YOLOv8

Supervision

OpenCV

Scikit-learn

NumPy
