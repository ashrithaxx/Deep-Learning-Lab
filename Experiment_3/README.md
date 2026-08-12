# Implementation of CNN for Image Classification

A TensorFlow/Keras implementation of a Convolutional Neural Network (CNN) for multi-class image classification on the CIFAR-10 dataset.

## Features
- CIFAR-10 data preprocessing
- Convolution, pooling, and feature map visualization
- CNN model implementation
- Max pooling vs average pooling comparison
- Model evaluation (Accuracy, Precision, Recall, F1-score)
- Training and evaluation visualizations

## Tech Stack
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn

## Results
- Test Accuracy: 64.36%
- Precision (macro): 65.59%
- Recall (macro): 64.36%
- F1-score (macro): 64.04%

## Contents
- `Implementation of CNN for Image Classification.ipynb` – Jupyter notebook with full implementation
- `Implementation of CNN for Image Classification.pdf` – Lab manual with theory, numerical examples, results, and discussion
- `images/` – Training and evaluation visualizations

## Setup
```bash
pip install -r requirements.txt
```

## Usage
Open and run `Experiment_3.ipynb` in Jupyter Notebook or JupyterLab. CIFAR-10 is loaded via `tf.keras.datasets.cifar10`, so no manual dataset download is required.

## Dataset
CIFAR-10 — 50,000 training / 10,000 testing images, 10 classes, 32×32×3.
