🛡️ CrowdGuard – AI Crowd Monitoring System

CrowdGuard is an AI-powered crowd analysis and safety monitoring system that detects people, counts crowd density, and evaluates risk levels using real-time video streams. It supports early warning during overcrowding and provides safe evacuation guidance.

📌 Overview

CrowdGuard uses computer vision and machine learning to monitor live webcam or CCTV footage. The system employs YOLOv8 for detecting people, OpenCV for video processing, and ML algorithms like KNN and SVM for crowd counting and risk assessment. When crowd density crosses a threshold, the system generates alerts and displays evacuation routes using the Google Maps API.

🛠 Tech Stack

Python

OpenCV

YOLOv8 (Ultralytics)

KNN & SVM for classification

Google Maps API for evacuation mapping

Flask / Web Interface (if included)

🚀 Features

👥 Real-Time People Detection via YOLOv8

🔢 Crowd Counting & Density Estimation

⚠️ Risk Assessment using ML models

🚨 Automatic Alert Generation

🗺 Evacuation Route Guidance

📊 Dashboard for Monitoring

📂 Project Structure

/models – YOLO and ML models

/web – Frontend files

crowdguard.py – Main detection script

risk_analysis.py – ML-based risk logic

maps.py – Evacuation route generation

utils.py – Helper functions

⚡ How to Run

Install required libraries:

pip install -r requirements.txt


Run the main program:

python crowdguard.py


Connect a webcam or use a video file for input.
