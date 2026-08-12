# Cataract Detection using CNN

A deep learning project for binary classification of eye images into **cataract** and **normal** classes using a Convolutional Neural Network (CNN).

## Overview

Cataracts are a common eye condition that can affect vision. This project explores the use of image classification to distinguish between cataract and normal eye images.

The model was trained on labeled eye images and evaluated on a separate test set.

## Approach

The project follows a standard image-classification pipeline:

1. Prepared and organized the cataract and normal image datasets.
2. Resized images to `224 × 224` pixels and normalized pixel values.
3. Used `ImageDataGenerator` for dataset preparation.
4. Built a sequential CNN consisting of convolutional, max-pooling, dense, and dropout layers.
5. Trained the model for 10 epochs.
6. Evaluated the trained model on the test dataset.
7. Tested the model on an individual eye image to verify inference.

## Model Architecture

The CNN consists of:

- Convolutional layers for feature extraction
- Max-pooling layers for spatial dimensionality reduction
- Dense layers for classification
- Dropout for regularization
- Sigmoid output for binary classification

## Technologies & Libraries

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Results

The model achieved **94.21% accuracy on the test dataset** consisting of 121 images.

The trained model was also used for individual image inference and correctly classified a sample cataract image.

> **Note:** This project is an academic machine-learning project and is not intended for clinical diagnosis or medical decision-making.

## Repository Structure

```text
cataract-detection/
│
├── notebook/
│   └── ds_capstone.ipynb
├── README.md
└── requirements.txt


