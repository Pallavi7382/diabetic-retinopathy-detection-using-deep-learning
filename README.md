# diabetic-retinopathy-detection-using-deep-learning
Diabetic Retinopathy Detection using Deep Learning

This project focuses on detecting the stages of Diabetic Retinopathy using deep learning models and comparing the performance of two powerful algorithms: EfficientNetB3 and EfficientNetB4.

Abstract

Diabetic Retinopathy (DR) is a diabetes complication that affects the eyes and can lead to blindness if not detected early. This project aims to build two deep learning models based on EfficientNetB3 and EfficientNetB4 architectures to automatically detect and classify the stage of diabetic retinopathy from retinal images. The final goal is to compare these models and identify the more efficient and accurate one for practical medical applications.

Dataset

Structure: The dataset consists of 5 folders, each representing a different class of diabetic retinopathy:
  - `No_DR`
  - `Mild`
  - `DR`
  - `Severe`
  - `Proliferate_DR`
Type: Image data
Total Images: ~3500 (approximate count based on folder sizes)

Project Objectives
Build a classification model using EfficientNetB3
Build another classification model using EfficientNetB4
Compare the performance of both models on the same dataset
Evaluate and visualize results using metrics like accuracy and confusion matrix

Techniques Used

Preprocessing
Data Augmentation: Rotation, flipping, color jitter
Loss Function: CrossEntropyLoss
Optimizer: AdamW
Learning Rate Scheduler: StepLR
Libraries: PyTorch, NumPy, Matplotlib, torchvision

Evaluation Metrics

| Model           | Accuracy |  
|----------------|----------|  
| EfficientNetB3 | 96.16%   |  
| EfficientNetB4 | 91.86%   |  

EfficientNetB3 showed superior performance in detecting diabetic retinopathy stages.

## 📈 Visualizations

Confusion Matrix to show per-class performance
Bar Graph showing class distribution
