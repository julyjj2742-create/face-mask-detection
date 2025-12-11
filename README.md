# Face Mask Detection
### *Final Project*

**Student:** Jaret Sanchez

**ITAI 1378 - Computer Vision & AI**

**Project Tier:** Tier 1

---
## The Problem
During the public health crisis, the whole world had to face wearing a face mask was crucial to avoid exposure. It was challenging to ensure that people wear face masks properly in public spaces.
The places that require mask compliance include hospitals, schools, airports, and government facilities.
This issue is important because manual monitoring is prone to human error; automated detection will improve face mask compliance and safety.

## Proposed Solution
My system will automatically detect if a person is wearing a mask correctly, not wearing a mask, and if the mask is being worn incorrectly.
Automated face mask detection will improve compliance and safety in public environments.

## Impact
[Who benefits? How much time/money saved? What's the value?]

## Technical Approach
- Technique: Object Detection
- Model: YOLOv8
- Framework: PyTorch
- Key libraries: 

## System Architecture
[Input image/webcam] → [YOLOv8 model interface] → [Gounding boxes + class labels] → [Output image with "mask"/"no mask"/"incorrect mask"]

## Dataset
- Source: Kaggle – Face Mask Detection Dataset
- Size: ~7,000 labeled images 
- Classes: With Mask, Without Mask, Incorrectly Worn Mask
- Split:
- Preprocessing:

## Installation & Setup
The project is designed to run in Google Colab.
Use the following to install dependencies:
pip install ultralytics opencv-python torch torchvision matplotlib pillow

After, open the notebook:
notebooks/Final_Project_FaceMaskDetection.ipynb

Run all cells to perform:
- Dataset preprocessing
- YOLOv8 training
-Model evaluation
- Prediction visualization

## Performance Metrics
Results from the validation set:

Metric	Value
Precision	0.902
Recall	0.780
mAP@0.5	0.869
mAP@0.5:0.95	0.630



## Week-by-week Plan
<img width="1339" height="706" alt="image" src="https://github.com/user-attachments/assets/b70a9bba-0b78-4f73-9166-92d02aeffccf" />

## Challenges & Backup Plans
<img width="884" height="595" alt="image" src="https://github.com/user-attachments/assets/bc74962a-80f0-4341-b812-3c2a10876e11" />

## Resources Needed
<img width="1120" height="702" alt="image" src="https://github.com/user-attachments/assets/8831ccf9-cf06-4798-9fa5-3b007081f6f9" />



