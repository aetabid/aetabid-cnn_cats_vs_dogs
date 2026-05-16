# 🐱🐶 Dogs vs Cats CNN Image Classifier

A Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify 
images of dogs and cats with 83.3% validation accuracy.

## 📊 Results

| Metric | Score |
|--------|-------|
| Baseline Accuracy | 67% |
| Final Validation Accuracy | **83.3%** |
| Improvement | +16 percentage points |
| Training Images | 20,000 |
| Validation Images | 5,000 |

## 🛠️ Improvements Made
- Added data augmentation (rotation, zoom, flips)
- Added Dropout(0.5) to reduce overfitting
- Removed training constraints for full dataset utilization
- Increased epochs from 5 to 15

## 🏗️ Model Architecture
- 3 Conv2D layers (32, 64, 128 filters)
- MaxPooling2D after each Conv layer
- Dropout(0.5) regularization
- Dense(512) hidden layer
- Sigmoid output for binary classification

## 🚀 Tech Stack
- Python, TensorFlow, Keras
- NumPy, Matplotlib
- Jupyter Notebook
