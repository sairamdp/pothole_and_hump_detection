# Intelligent Road Damage Detection Using YOLOv8n

## Project Overview

This project develops a deep learning-based road damage detection system using YOLOv8n to identify:

- Potholes
- Speed Bumps

The model uses transfer learning and a custom annotated dataset to improve detection accuracy and performance.

## Dataset

- Source: Roboflow
- Classes: Pothole and Speed Bump
- Format: YOLO
- Split: Training, Validation, and Testing
- Validation Instances: 978

## Model Training

| Parameter | Value |
|---|---|
| Model | YOLOv8n |
| Epochs | 40 |
| Image Size | 640 × 640 |
| Batch Size | 16 |
| GPU | NVIDIA Tesla T4 |
| Platform | Google Colab |

## Results

| Metric | Custom Model | Fine-Tuned YOLOv8n |
|---|---:|---:|
| Precision | 63.30% | 80.28% |
| Recall | 56.08% | 68.02% |
| mAP50 | 59.07% | 73.42% |
| mAP50-95 | 24.76% | 35.28% |
| FPS | 231.74 | 237.58 |

## Technologies Used

- Python
- YOLOv8n
- Ultralytics
- Deep Learning
- Computer Vision
- Roboflow
- Google Colab

## Applications

- Automated road inspection
- Pothole and speed bump detection
- Smart city monitoring
- Road maintenance planning

## Conclusion

The fine-tuned YOLOv8n model achieved 80.28% Precision, 68.02% Recall, 73.42% mAP50, and 237.58 FPS, demonstrating its potential for automated road damage detection and real-time monitoring.
