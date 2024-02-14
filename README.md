# Flower-recognition-using-CNN

## Overview
This repository contains a Jupyter notebook for building a neural network model to recognize flowers based on the Kaggle dataset (https://www.kaggle.com/datasets/alxmamaev/flowers-recognition). The model is built using TensorFlow and leverages the VGG19 pre-trained model.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Testing on External Images](#testing-on-external-images)
- [Results](#results)

## Prerequisites
- Python
- Jupyter Notebook
- TensorFlow
- Kaggle API key (for downloading the dataset)

## Getting Started
1. Clone the repository.
   ```bash
   git clone https://github.com/yagnavalkinis/flowers-recognition-using-CNN.git
   cd flowers-recognition-using-CNN

## Dataset
The dataset used in this project is alxmamaev/flowers-recognition from Kaggle. The dataset is divided into five classes: daisy, tulip, rose, sunflower, and dandelion.

## Data Preprocessing
- The images are resized to 224x224 pixels.
- Corrupted and unusual images are handled.

## Model Architecture
The model utilizes the VGG19 pre-trained model with additional layers for classification.

## Training
The model is trained for 10 epochs with early stopping and learning rate reduction callbacks.

## Evaluation
The model is evaluated on a test set, and classification reports and confusion matrices are provided.

## Testing On External Images
You can test the model on your own images using the provided notebook.

## Results
The repository includes visualizations of correctly and misclassified images, as well as model performance metrics.
