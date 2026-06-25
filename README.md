# Median Nerve Segmentation — CNN-Based Medical Imaging

Research internship project at the **Medical Imaging Group, Indian Institute of Science (IISc), Bangalore**
Supervised by Prof. Phaneendra K · Oct 2023 – Mar 2024

## Overview
Developed a deep learning pipeline to automatically localise the median nerve in wrist 
ultrasound scans — a task relevant to carpal tunnel syndrome diagnosis. The model removes 
the need for manual annotation by clinicians, reducing diagnosis time.

## Method
- Architecture: U-Net convolutional neural network for semantic segmentation
- Framework: TensorFlow / Keras
- Preprocessing: denoising, normalisation, and augmentation pipeline built with NumPy and OpenCV
- Dataset: wrist ultrasound images provided by the MIG lab at IISc (not publicly available)

## Results
Achieved **94.6% Dice coefficient** on held-out test set.

## Stack
Python · TensorFlow · Keras · NumPy · OpenCV · Jupyter

## Results
![image](https://github.com/user-attachments/assets/9cb29fd2-ccdf-4e2a-8d09-1d038e7359cc)
