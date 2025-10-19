# 🛠️ Object Detection using OpenCV SSD MobileNet

A Python project for **real-time object detection** using **OpenCV’s DNN module** and the **SSD MobileNet v3 COCO model**. It supports both **image** and **video/webcam detection** with bounding boxes and confidence scores.

---
## 🔹 Project preview
## 📸 Screenshot

![Object Detection Interface](https://raw.githubusercontent.com/Ayush2049/OBJECT-DETECTION--THROUGH-IMAGE-VIDEO-AND-WEBCAM/57f2b7a7e7b38f90fa4b8b55282dbdfb58bdbe2e/project-instances/Screenshot%202025-10-19%20125811.png)

*A snapshot of the object detection interface.*

---

## 🎥 Video Demonstration

[![Watch Video](https://raw.githubusercontent.com/Ayush2049/OBJECT-DETECTION--THROUGH-IMAGE-VIDEO-AND-WEBCAM/main/project-instances/video_thumbnail.png)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

*Click the thumbnail to watch the demonstration video.*

---
## 🔹 Features

- Detects **80 object classes** from the COCO dataset  
- Works on **images**, **video files**, and **live webcam feed**  
- Displays **bounding boxes** and **labels with confidence scores**  
- Uses **SSD MobileNet v3** for efficient and fast detection  

---

## 📂 Project Structure

- `frozen_inference_graph.pb` – Pretrained SSD MobileNet model  
- `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt` – Model configuration file  
- `Labels.txt` – COCO class labels (80 classes)  
- `images/` – Example images and video for testing  
- `object_detection.py` – Main Python script for detection  

---

## ⚡ Installation

**Python dependencies:**
```bash
pip install opencv-python matplotlib
