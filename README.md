# Brain-MRI-Tumor-Classification using Transfer Learning

## Overview

This project implements a deep learning pipeline for classifying Brain MRI images into four categories using Transfer Learning with ResNet18.

## Dataset

Public Brain MRI Tumor Dataset

Classes

- Glioma
- Meningioma
- Pituitary
- No Tumor

## Pipeline

MRI Images

↓

Resize (224x224)

↓

Normalization

↓

ResNet18

↓

Prediction

↓

Evaluation

## Technologies

- Python
- PyTorch
- Transfer Learning
- NumPy
- Matplotlib

## Results

The pretrained ResNet18 model achieved high classification accuracy on the testing dataset after fine-tuning for three epochs.

## Trained Model

The trained model (`brain_model.pth`) can be downloaded from Google Drive:

👉 **Download Model:** https://drive.google.com/file/d/YOUR_FILE_ID/view?usp=sharing

## Future Improvements

- U-Net Segmentation
- Vision Transformers
- Grad-CAM Explainability
