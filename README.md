# 🚀 YOLOv5 Real-Time Object Detection System

This project implements a real-time object detection system using **YOLOv5** and **Python**. It leverages pre-trained models to detect multiple objects in live camera feeds or video streams with high accuracy and speed. The system is designed for performance, flexibility, and easy customization with custom datasets.

## 📌 Features

- 🧠 Powered by **YOLOv5** (You Only Look Once v5)
- 🔍 Real-time object detection using webcam or video
- 📁 Support for **custom datasets**
- ⚡ Fast inference with **PyTorch**
- ✅ Adjustable confidence and IoU thresholds
- 🖼️ Saves detection results with bounding boxes and labels

## 📦 Project Structure
├── detect.py # Main detection script
├── data/ # Data-related config files
├── models/ # YOLOv5 model definitions
├── runs/ # Output folder for results
├── weights/ # Folder for storing model weights
├── requirements.txt # Python dependencies
└── README.md # Project documentation
## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Ujjawal-Singh/Object-Detection-Using-YOLO5.git
cd Object-Detection-Using-YOLO5

### 2. Install Dependencies

Make sure Python 3.7+ and pip are installed. Then run:

```bash
pip install -r requirements.txt

🧠 Model Options
- yolov5s.pt – small (fastest, less accurate)
- yolov5m.pt – medium
- yolov5l.pt – large
- yolov5x.pt – extra large (most accurate, slowest)

🧑‍💻 Technologies Used
- Python 3.8+
- YOLOv5
- PyTorch
- OpenCV
- NumPy

📌 Applications
- Surveillance Systems
- Traffic Monitoring
- Industrial Automation
- Smart Retail and Inventory Detection
- Assistive AI Devices
