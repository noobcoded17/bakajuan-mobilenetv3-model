# BakaJuan MobileNetV3 Model

A deep learning model for mangrove species classification using MobileNetV3-Small, transfer learning, fine-tuning, temperature scaling, and TensorFlow Lite deployment.

## Overview

This repository contains the training pipeline used in the BakaJuan Android application for identifying mangrove species from leaf images.

The model was developed using TensorFlow and Keras and optimized for mobile deployment through TensorFlow Lite.

## Features

- MobileNetV3-Small transfer learning
- Image data augmentation
- Fine-tuning
- Temperature scaling calibration
- TensorFlow Lite (.tflite) export
- Confusion matrix and classification report
- Training and validation performance visualization

## Dataset

The model was trained using images of the following mangrove species:

- Bakhaw Lalaki (*Rhizophora apiculata*)
- Bakhaw Babae (*Rhizophora mucronata*)
- Pagatpat (*Sonneratia alba*)
- Bungalon (*Avicennia marina*)
- Buta-buta (*Excoecaria agallocha*)

## Model Architecture

- TensorFlow / Keras
- MobileNetV3-Small
- Transfer Learning
- Fine-Tuning
- Temperature Scaling
- TensorFlow Lite

## Results

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Repository Contents

├── model_training.ipynb
├── final_model.tflite
├── saved_model/
├── images/
└── README.md

## Requirements

- Python 3.10+
- TensorFlow
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn

## Author

JESSA MAE V. SOLANO
BS Information Technology
