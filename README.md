# Distracted Driver Detection with YOLOv8 🚗📱

![Demo](assets/detection_demo.gif)

A high-accuracy computer vision system that detects 10 types of distracted driving behaviors in real-time using YOLOv8.

## Key Results 

- **97.8%** overall accuracy
- **100%** recall on critical classes (texting, phone use)
- Runs at **38 FPS** on edge devices

### Top Performers:
| Behavior       | Precision | Recall |
|----------------|-----------|--------|
| Texting Right  | 100%      | 99.5%  |
| Phone Talking  | 97.5%     | 100%   |
| Reaching Behind| 100%      | 100%   |

## Quick Start 

1. Install requirements:
```bash
pip install ultralytics opencv-python
Run detection:

python
from ultralytics import YOLO
model = YOLO('best.pt')
results = model.predict('input.mp4', show=True)
Features 
Real-time detection (30+ FPS)

Optimized for edge deployment

Custom-trained on State Farm dataset

HSV-augmented training data
