# Real-Time Object Detection with YOLO and Android Integration

## Overview
This project implements a complete solution for real-time object detection. It includes:
- A deep learning component using YOLO for training, validation, and TF Lite export.
- An Android application that integrates the exported TF Lite model for on-device inference.

## Deep Learning Model Training & TF Lite Export
- Train your custom YOLO model using the provided notebooks.
- Export the trained model to TensorFlow Lite format.
- Review the `train_export_yolov8_model.ipynb` and `Deep_Learning_Project.ipynb` notebooks for detailed instructions.
- Use the exported `.tflite` model along with its labels in the Android app.

## Features
- Real-time object detection on live video feeds.
- High accuracy with YOLOv10 architecture.
- Easy integration with various input sources.
- Optimized for performance and scalability.

## Prerequisites
- Python 3.7+ with necessary libraries (e.g., OpenCV, ultralytics)
- TensorFlow Lite and related dependencies for model export
- Android Studio for building and deploying the Android application

## Installation & Usage
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/object_detection_realtime.git
   ```
2. For deep learning tasks:
   - Open and run the provided notebooks to train and export your model.
3. For Android deployment:
   - Place the exported TF Lite model and labels in the specified assets folder.
   - Open the Android project in Android Studio.
   - Build and run the project on your Android device.

## Contributing
Contributions are welcome. Please open issues or submit pull requests for improvements and bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
