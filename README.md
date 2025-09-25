# FireSight--Early-Forest-Fire-Detection
Deep learning pipeline for early forest fire detection using UAV visible + infrared imagery with YOLOv5 and TWMM.

## Project File
The main notebook and dataset are available via Google Drive.  
Access is restricted — please request access if needed: [Request Access Here](https://colab.research.google.com/drive/1skZN18Dy7rnAMsGq9l8dT0ku79mwQ1Q4?usp=sharing)

Leveraged a dataset of 2,752 synchronized visible–infrared UAV image pairs, enhancing YOLOv5s for robust
small-target detection.

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

## sample image pairs

<img width="1093" height="525" alt="Screenshot 2025-09-26 003646" src="https://github.com/user-attachments/assets/c42f28c1-70f5-4cf8-89ae-42d387ed6a42" />
<img width="1090" height="547" alt="Screenshot 2025-09-26 003721" src="https://github.com/user-attachments/assets/0bf419fe-1fdd-4a71-8509-0857583ee8a4" />

## Output

<img width="1732" height="630" alt="Screenshot 2025-09-26 003849" src="https://github.com/user-attachments/assets/cb167b45-7630-44bc-8c0e-0176f3ab44e7" />
<img width="812" height="803" alt="Screenshot 2025-09-26 003924" src="https://github.com/user-attachments/assets/0c2909bb-95aa-4397-b6b6-939665f78ae5" />
