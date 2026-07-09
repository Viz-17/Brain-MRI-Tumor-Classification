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

## Future Improvements

- U-Net Segmentation
- Vision Transformers
- Grad-CAM Explainability
