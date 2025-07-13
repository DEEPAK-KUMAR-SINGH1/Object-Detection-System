# Object-Detection-System
Object Detection AI using OpenCV Built a real-time object detection system using Haar Cascade Classifier in OpenCV. The project processes video frames, detects object, draws bounding boxes with labels, and displays cropped images of detected object. Ideal for beginner-level computer vision applications.
# 🚗 Car Detection Docker App

This container accepts a folder of images, detects cars using Haar Cascade, and saves the output with bounding boxes.

## 🧪 Run Locally

```bash
docker build -t car-detector .
docker run -v /path/to/images:/input -v /path/to/save:/output car-detector
