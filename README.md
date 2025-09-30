# Breast Cancer Classification

This project uses TensorFlow/Keras to classify breast cancer tumors (malignant vs benign) using the sklearn breast cancer dataset.

## Features
- 30 numeric features
- Binary classification (0 = malignant, 1 = benign)

## Model Architecture
- Input: 30 features
- Hidden layer: Dense(16, activation='relu')
- Output layer: Dense(1, activation='sigmoid')

## How to Run
```bash
pip install -r requirements.txt
python train_model.py
