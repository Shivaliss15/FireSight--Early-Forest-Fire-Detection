# FireSight--Early-Forest-Fire-Detection
Deep learning pipeline for early forest fire detection using UAV visible + infrared imagery with YOLOv5 and TWMM.

## Project File
The main notebook and dataset are available via Google Drive.  
Access is restricted — please request access if needed: [Request Access Here](https://colab.research.google.com/drive/1skZN18Dy7rnAMsGq9l8dT0ku79mwQ1Q4?usp=sharing)


# 🌲 Early Forest Fire Detection using UAV Image Fusion
## 📌 Overview

This project focuses on early detection of forest fires using UAV (drone) images captured from visible (VIS) and infrared (IR) sensors.
It combines image registration, fusion techniques, and deep learning (YOLOv5) to improve early fire detection and response.

The main workflow includes:

Image Registration – Aligning VIS and IR images using the TWMM method.

Image Fusion – Combining registered images into a single enhanced image.

Evaluation – Measuring fusion quality using standard image metrics.

YOLOv5 Training – Detecting potential fire regions using deep learning.

## ✨ Features

UAV-based fire monitoring system.

Robust image registration for precise alignment.

Image fusion to enhance details from both VIS and IR inputs.

Custom YOLOv5 training pipeline for fire detection.

End-to-end workflow implemented in a single Google Colab notebook.

## 🛠️ Tech Stack

Python, OpenCV, NumPy, Matplotlib

YOLOv5 (PyTorch)

Google Colab for development and training

## 🚀 Getting Started
1. Clone the Repository
git clone [https://...]
cd early-forest-fire-detection

2. Install Dependencies
pip install -r requirements.txt

3. Run in Google Colab

Open the notebook 1_Early_forest_fire_detection.ipynb.

Mount Google Drive (if using Drive for storage).

Follow the step-by-step workflow.

## 📊 Project Structure
FireSight--Early-Forest-Fire-Detection/
│
├── 1_Early_forest_fire_detection.ipynb  # Main notebook
├── requirements.txt                      # Dependencies
└── README.md                             # Project documentation

## 🔮 Future Improvements

Real-time UAV-based fire detection and alerts.

Deep learning-based image fusion techniques.

Deployment as a web or mobile application.

