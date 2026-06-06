
# Vehicle Detection from LiDAR Imagery Using Deep Learning

## Overview
This project presents a LiDAR-based vehicle detection system designed for autonomous driving applications. The system utilizes 3D LiDAR point cloud data from the KITTI dataset and applies deep learning techniques to accurately detect and localize vehicles in real-world driving environments.

To efficiently process sparse and unstructured LiDAR data, the point clouds are converted into a Bird's Eye View (BEV) representation. The generated BEV feature maps are then used as input to a deep learning model for vehicle detection and 3D bounding box estimation.

## Features
- Vehicle detection using 3D LiDAR point clouds
- Bird's Eye View (BEV) feature representation
- Deep learning-based object detection
- 3D bounding box generation and visualization
- KITTI dataset support
- Real-time detection capability
- Visualization in BEV and Camera View

## Dataset
The project uses the KITTI Object Detection Dataset, which provides:
- LiDAR Point Clouds (.bin)
- RGB Images (.png)
- Calibration Files (.txt)
- Ground Truth Labels (.txt)

## Technologies Used
- Python
- PyTorch
- Darknet
- NumPy
- OpenCV
- Matplotlib
- KITTI Dataset

## Methodology
1. Data Acquisition from KITTI Dataset
2. LiDAR Point Cloud Preprocessing
3. Bird's Eye View (BEV) Generation
4. Feature Extraction using Deep Learning
5. Vehicle Detection and Localization
6. 3D Bounding Box Estimation
7. Result Visualization

## Applications
- Autonomous Vehicles
- Advanced Driver Assistance Systems (ADAS)
- Intelligent Transportation Systems
- Traffic Monitoring and Analysis

## Author

Yash Vilas Daphale


