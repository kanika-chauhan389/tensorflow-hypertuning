## TensorFlow Hyperparameter Tuning

This repository contains a **Jupyter Notebook** that demonstrates **hyperparameter tuning** in **TensorFlow and Keras** using **Keras Tuner**.  
It helps you systematically optimize deep learning models for better accuracy, faster convergence, and efficient architectures.

---

## 📌 Overview
- Builds a **Convolutional Neural Network (CNN)** using TensorFlow/Keras.  
- Tunes key hyperparameters such as:
  - Number of filters
  - Learning rate
  - Batch size
  - Number of layers
- Visualizes training performance and compares tuned vs. untuned models.

---

## 📂 Dataset
- The notebook uses the **CIFAR-10 dataset** (60,000 images, 10 classes) as an example for demonstration.
- The workflow is **dataset-agnostic** and can easily be adapted for:
  - Custom image datasets (e.g., agricultural, medical, or industrial images)
  - Different input sizes or number of classes

To adapt to your own dataset:
1. Replace the CIFAR-10 data loading and preprocessing section with your custom data pipeline.
2. Adjust the model input shape and output classes accordingly.

---

## 🛠 Requirements
- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- NumPy


