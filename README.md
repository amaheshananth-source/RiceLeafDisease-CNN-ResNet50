Rice Leaf Disease Detection 🌾

This repository contains a deep learning project for classifying rice leaf diseases using image‑based techniques. The goal is to support early disease detection and improve crop management by automating the identification process.

Key Features:

Dataset of 119 rice leaf images across three classes:

Leaf Smut (39)

Brown Spot (40)

Bacterial Leaf Blight (40)

Data Analysis: Examined dataset structure, class distribution, and image properties.

Preprocessing: Image resizing, normalization, and label encoding.

Model Development:

Custom Convolutional Neural Network (CNN)

ResNet50 Transfer Learning with pretrained ImageNet weights

Data Augmentation: Rotation, flipping, zooming, and translation to improve generalization.

Evaluation Metrics: Accuracy, precision, recall, F1‑score, confusion matrix, and training/validation curves.

Results:

CNN achieved reasonable accuracy.

ResNet50 achieved superior performance (~90%), making it the recommended model for deployment.

Conclusion:  
This project provides a complete workflow for rice leaf disease detection, covering data analysis, preprocessing, augmentation, model development, and evaluation. It serves as a foundation for future research with larger datasets and real‑world agricultural applications.
