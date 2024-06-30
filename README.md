# 🛠️ PPE Detection on Worksites

This project leverages the YOLOv8 model to detect Personal Protective Equipment (PPE) such as helmets, safety vests, and eyewear on worksites using annotated images for training. The model was tested for accuracy and applied to real-time video footage to effectively identify PPE, aiming to enhance workplace safety.

## Project Overview
The objective of this project is to improve workplace safety by enabling real-time detection of PPE for compliance monitoring and safety enforcement. To achieve this, we trained the YOLOv8 model using annotated images, tested it for accuracy, and applied it to real-time video footage.

## Motivation
Ensuring workers wear proper PPE is crucial for safety. Manual checks are often slow and prone to mistakes. This project uses advanced AI to automatically and quickly detect PPE in real-time, helping to prevent accidents and ensure everyone follows safety rules. This approach makes worksites safer and more efficient.

## Code and Resources Used
We used Python version 3.8 along with packages such as ultralytics, opencv, numpy, torch, matplotlib, and roboflow. To install the necessary packages, you can use the command `pip install -r requirements.txt`. For more details on YOLOv8, refer to the [YOLOv8 Documentation](https://github.com/ultralytics/yolov8). Detailed steps and findings are available in the provided notebook and additional documentation.

## Data Collection
Images were annotated using Roboflow, with the original images sourced from an appropriate dataset.

## Exploratory Data Analysis (EDA)
We visualized annotated images to understand the distribution and variety of PPE, analyzed image quality and annotation accuracy, and assessed different worksite conditions and PPE in various scenarios.

## Model Deployment
The trained model was successfully deployed on real-time video footage to demonstrate its practical application. As shown in the video below, the model effectively detects helmets and reflectors in dynamic worksite environments, ensuring real-time compliance and safety monitoring.

![Real-Time PPE Detection](Output1-ezgif.com-video-to-gif-converter.gif)

