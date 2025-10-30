# face mask detection
Computer Vision Project - Face Mask Detection

**Team Member:** Jaret Sanchez (julyjj2742@gmail.com)

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

## Technical Approach
- Technique: Object Detection
- Model: YOLOv8
- Framework: PyTorch

The reason why I chose to use YOLOv8 is because this real-time object detection model is the best option for detecting multiple faces and mask types in one frame.

## Data Plan
- Source: Kaggle – Face Mask Detection Dataset
- Size: ~7,000 labeled images 
- Labels: With Mask, Without Mask, Incorrectly Worn Mask

Preparation: 
Download and verify the dataset
Split into training, validation, and testing sets
Convert annotations into YOLO format if needed

## System Diagram
<img width="1714" height="596" alt="image" src="https://github.com/user-attachments/assets/5fcbca34-aa03-406b-924e-755d61cb7435" />

## Sucess Metrics
<img width="1340" height="481" alt="image" src="https://github.com/user-attachments/assets/3d95b845-e3e2-46e0-bc81-bf5e29b563f2" />

## Week-by-week Plan
<img width="1339" height="706" alt="image" src="https://github.com/user-attachments/assets/b70a9bba-0b78-4f73-9166-92d02aeffccf" />

## Challenges & Backup Plans
<img width="884" height="595" alt="image" src="https://github.com/user-attachments/assets/bc74962a-80f0-4341-b812-3c2a10876e11" />

## Resources Needed
<img width="1120" height="702" alt="image" src="https://github.com/user-attachments/assets/8831ccf9-cf06-4798-9fa5-3b007081f6f9" />



