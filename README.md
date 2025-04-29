# Broken_Railway_Detection
Project Overview
Accidents resulting from defective railway tracks and derailments are a frequent and serious concern, especially in Southeast Asian countries. Early and accurate detection of track faults is critical to prevent such disasters. However, manual inspection methods are often time-consuming, labor-intensive, and expensive.

To address this, a series of four notebooks were developed to explore different automated fault detection approaches, using a publicly available railway track dataset from Kaggle:
Railway Track Fault Detection Dataset.

Classical Machine Learning:
Using traditional techniques such as Support Vector Machine (SVM), Logistic Regression, and Random Forest classifiers on hand-crafted HOG features.

CNN-based Classification (without Augmentation): Training convolutional neural network models on the original dataset to classify defective and non-defective railway tracks.

CNN-based Classification (with Data Augmentation): Enhancing the training data through augmentation techniques to improve model generalization and robustness.

Anomaly Detection using Autoencoder: Training a UNet-style convolutional autoencoder exclusively on healthy track images and detecting faults based on reconstruction error analysis.

This multi-approach study provides a comprehensive evaluation of both classical and deep learning methods for automatic railway track fault detection.
