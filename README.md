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

- 
## Results

### Classification Report


              precision    recall  f1-score   support

    airplane       0.69      0.79      0.74      1000
  automobile       0.80      0.85      0.82      1000
        bird       0.61      0.62      0.62      1000
         cat       0.54      0.54      0.54      1000
        deer       0.68      0.60      0.64      1000
         dog       0.63      0.58      0.61      1000
        frog       0.74      0.84      0.79      1000
       horse       0.79      0.71      0.75      1000
        ship       0.88      0.75      0.81      1000
       truck       0.75      0.82      0.78      1000

    accuracy                           0.71     10000
   macro avg       0.71      0.71      0.71     10000
weighted avg       0.71      0.71      0.71     10000

