# 🎯 Attention Tracker

This project focuses on video analysis, object detection, object tracking, and trajectory prediction.

## 💡 Overview

The project utilizes various techniques and models for analyzing video streams, including:

*   **Object Detection:** YOLOv8 (`yolo_v8_tryout.py`) and DETR (Detection Transformer) with ResNet-50 (`detr_resnet_50.py`) are used for object detection.
*   **Object Tracking:**  The `object_tracking_script.py` is responsible for tracking detected objects across video frames.
*   **Trajectory Prediction:** The `predict_trajectory_vector.py` script predicts the trajectories of tracked objects.
*   **Video Streaming:** The `video_feed.py` and `video_stream_script.py` handle video input and streaming.
*   **Attraction Matrix:** The `get_attraction_matrix.py` calculates an attraction matrix, likely used for understanding relationships between objects.
*   **Object List:** The `get_object_list.py` retrieves a list of objects.

## 📄 Files

*   `detr_resnet_50.py`: Implements object detection using DETR with a ResNet-50 backbone.
*   `get_attraction_matrix.py`: Calculates the attraction matrix between objects.
*   `get_object_list.py`: Retrieves a list of detected objects.
*   `object_tracking_script.py`: Implements object tracking.
*   `predict_trajectory_vector.py`: Predicts the trajectory of objects.
*   `video_feed.py`: Provides video feed input.
*   `video_stream_script.py`: Handles video streaming.
*   `yolo_v8_tryout.py`: Implements object detection using YOLOv8.

## 🚀 Usage

To use this project, you will need to install the necessary dependencies and configure the video input. Please refer to the individual script files for specific instructions.

## ⚙️ Dependencies

*   PyTorch
*   TorchVision
*   Transformers
*   OpenCV
*   Other common data science libraries (NumPy, SciPy, etc.)

## 📝 License

This project is licensed under a **Proprietary License**.

It is intended for **personal use, educational purposes, and portfolio demonstration only**.
**Commercial use, distribution, modification, or resale is strictly prohibited without explicit written permission from the author.**

See the [LICENSE](./LICENSE) file for full license details.
