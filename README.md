# Project Title: Automated Brain Tumor Segmentation using U-Net

# Project Overview:

This project implements a deep learning system for the automated detection and segmentation of brain tumors from MRI scans. Utilizing a U-Net architecture, the model performs pixel-level classification to distinguish between healthy brain tissue and structural abnormalities (pathologies).

# Technical Implementation:

1. Preprocessing: Implemented Gaussian noise removal and min-max normalization via OpenCV to enhance image quality and stabilize training.
2. Architecture: Developed a Convolutional Neural Network (CNN) based on the U-Net framework, featuring an encoder-decoder structure with skip connections to preserve spatial information.
3. Dataset: Trained on the LGG MRI Segmentation dataset, utilizing data augmentation (rotations and flips) to improve model generalization.
4. Evaluation: The system was evaluated using medical-grade metrics, specifically the Dice Coefficient and Intersection over Union (IoU), to quantify the accuracy of the overlap between AI predictions and radiologist-verified ground truth masks.

# Tools Used:

1. Python
2. Keras/TensorFlow
3. OpenCV
4. Matplotlib.
