# Comprehensive Study of CNN Training, Regularization, Optimization, Hyperparameter Tuning, Transfer Learning and Cross-Validation

A MobileNetV2-based study of image classification on the Oxford-IIIT Pet dataset, covering weight initialization, regularization, optimization, hyperparameter tuning, transfer learning, fine-tuning, and 5-fold cross-validation.

## Features

- Oxford-IIIT Pet dataset preprocessing
- MobileNetV2 CNN implementation
- Weight initialization comparison
- Regularization and overfitting analysis
- Batch Normalization analysis
- SGD, Momentum, RMSProp, and Adam comparison
- CNN hyperparameter tuning
- Transfer learning and fine-tuning
- 5-fold cross-validation
- Confusion matrix and misclassified image analysis
- Training and evaluation visualizations

## Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn

## Results

- Best Scratch Validation Accuracy: 15.08%
- Fine-Tuned Validation Accuracy: 91.30%
- Cross-Validation Accuracy: 88.32% ± 0.93%
- Test Accuracy: 87.90%
- Precision (macro): 88.29%
- Recall (macro): 87.82%
- F1-score (macro): 87.79%

## Setup

```bash
pip install -r requirements.txt
