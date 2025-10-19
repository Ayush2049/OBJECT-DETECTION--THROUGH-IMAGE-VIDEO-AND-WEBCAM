# 🛠️ Object Detection using OpenCV SSD MobileNet

A Python project for **real-time object detection** using **OpenCV’s DNN module** and the **SSD MobileNet v3 COCO model**. It supports both **image** and **video/webcam detection** with bounding boxes and confidence scores.

---
## 🔹 Project preview

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
