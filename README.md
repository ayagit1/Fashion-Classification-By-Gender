# Gender Classification on Fashion Dataset

This project implements a **Gender Classification** model using a **Convolutional Neural Network (CNN)**, designed to classify fashion images into five categories: Men, Women, Boys, Girls, and Unisex.

## Overview

The model uses a CNN architecture to predict the gender and category of fashion images from a labeled dataset. It utilizes convolutional layers for feature extraction and dense layers for classification.

## Dataset

The dataset contains images categorized by gender and other attributes like season, usage, and color. The goal is to classify each image into one of the following categories:
- **Men**
- **Women**
- **Boys**
- **Girls**
- **Unisex**

Dataset Source: [Fashion Product Images (Small) on Kaggle](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)

## Model Architecture

- **Input Shape**: `(80, 60, 3)` (80x60 RGB images)
- **Convolutional Layers**: Used for extracting features from images
- **Dense Layers**: Final classification into 5 categories
- **Dropout**: Applied to avoid overfitting
- **Optimizer**: Adam optimizer

## Results

- **Accuracy**: 91.45% after 15 epochs
- **Precision, Recall, F1-Score**: 0.7401
- **Loss**: Reduced from 1.5066 to 0.2311 during training

## Installation

To run this project locally, ensure you have Python 3.x and the following libraries installed:

```bash
pip install tensorflow numpy matplotlib pandas
```

## Usage

Run the model using the provided Jupyter notebook or Python script. After training, the model can be used to classify new images based on gender.

## Future Work

- **Model Deployment**: The next step will be deploying the model on a cloud platform like GCP or AWS.
- **Fine-Tuning**: Explore hyperparameter tuning for improved performance.
