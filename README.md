# Brain Tumor Segmentation with U-Net

Automated brain tumor segmentation from MRI images using a U-Net deep learning architecture.

## Project Overview

This project implements a U-Net-based convolutional neural network for segmenting brain tumors from MRI scans. Accurate tumor segmentation is crucial for clinical diagnosis and treatment planning, and this model aims to provide a reliable and efficient automated solution.

## Features

- MRI Image and mask preprocessing pipeline.
- U-Net model implementation from scratch using TensorFlow/Keras.
- Evaluation metrics: Dice coefficient, IoU (Intersection over Union).
- Visualization of predictions vs. ground truth.

## Dataset Details

The dataset used is the **[Brain Tumor Segmentation dataset](https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation)** by *nikhilroxtomar* on Kaggle, which contains 3,264 labeled MRI images and their corresponding binary masks.

- Format: PNG images.
- Each MRI image has a corresponding segmentation mask.
- Dataset Source: [Kaggle Dataset](https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation)

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy / OpenCV
- Matplotlib

## Model Architecture

This project uses the **U-Net architecture**, a proven model for biomedical image segmentation. U-Net’s encoder-decoder structure and skip connections allow for precise localization and segmentation of tumor regions.

## Results

The model achieves strong performance in segmenting tumor regions, demonstrating solid overlap between predicted and ground truth masks.

- **Dice Coefficient**: 0.79
- **IoU (Intersection over Union)**: 0.65
- **Loss**: 0.21

These results indicate that the U-Net model is effective at learning tumor boundaries in MRI images. Sample segmentation outputs and visual comparisons between predicted and actual tumor regions are available in the notebook for qualitative assessment.
