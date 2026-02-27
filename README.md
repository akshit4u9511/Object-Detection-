🚀 Real-Time Object Detection using MobileNet-SSD
![Object Detection Demo](https://github.com/akshit4u9511/Object-Detection-/blob/ce5db8f92e714b10cf0c056d6d7b443b728244b7/demo/bottle%20detect.png)

A real-time object detection system built using Python, OpenCV, and Deep Learning (CNNs). This project uses the MobileNet-SSD (Single Shot Detector) architecture for fast and efficient object detection on live video streams.

📌 Overview

This project performs real-time object detection using a pre-trained MobileNet-SSD model. It detects multiple objects in a live camera feed and draws bounding boxes with class labels and confidence scores.

The system is lightweight, fast, and optimized for edge devices and real-time applications.

🧠 Model Details

Model: MobileNet-SSD

Framework: Caffe

Architecture: Convolutional Neural Network (CNN)

Type: Single Shot MultiBox Detector

Optimized for low computational cost and real-time inference

🛠️ Tech Stack

Python

OpenCV

NumPy

Deep Learning

Caffe Pre-trained Model

📂 Project Structure

Object-Detection/
│
├── real_time_object_detection.py
├── MobileNetSSD_deploy.caffemodel
├── MobileNetSSD_deploy.prototxt.txt
├── .gitignore
└── README.md

▶️ How to Run
1️⃣ Clone the Repository

git clone https://github.com/akshit4u9511/Object-Detection.git

cd Object-Detection

2️⃣ Install Dependencies

pip install opencv-python numpy

3️⃣ Run the Application

python real_time_object_detection.py

Your webcam will open and begin detecting objects in real time.
Press q to exit.

🎯 Features

Real-time webcam object detection

Fast inference using MobileNet backbone

Lightweight and efficient architecture

Bounding boxes with confidence scores

Multi-class object detection

Easy to deploy and modify

📊 Supported Object Classes

The model can detect 20+ object categories including:

Person

Bottle

Car

Chair

Dog

Cat

TV Monitor

Bicycle

Bus

Aeroplane

And more

🔥 Applications

Smart Surveillance Systems

Retail Object Monitoring

Assistive AI Systems

Autonomous Robotics

Computer Vision Learning Projects

Edge AI Deployment

👨‍💻 Author

Akshit Sharma
B.Tech Computer Science
Interested in AI, Machine Learning, and Real-Time Systems
