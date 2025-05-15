# 🧠 CIFAR-10 Image Classification with PyTorch

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset. It includes training, evaluation, visualization, and performance metrics — all in one script.

---

## 📁 Project Overview

- **Framework**: PyTorch  
- **Dataset**: CIFAR-10  
- **Model**: Custom CNN  
- **Features**:
  - Data loading and preprocessing
  - CNN model definition
  - Training loop
  - Evaluation on test data
  - Confusion matrix & classification report
  - Sample predictions visualization

---

## 🖼 Dataset: CIFAR-10

- 60,000 32×32 color images in 10 classes
- 10,000 test images
- Classes: `airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`

---

## 🔧 Requirements

Install dependencies with pip:

```bash
pip install torch torchvision matplotlib seaborn scikit-learn
              precision    recall  f1-score   support

    airplane       0.74      0.74      0.74       100
  automobile       0.86      0.85      0.85       100
        bird       0.56      0.49      0.52       100
         cat       0.48      0.49      0.48       100
        deer       0.66      0.68      0.67       100
         dog       0.64      0.62      0.63       100
        frog       0.76      0.82      0.79       100
       horse       0.78      0.76      0.77       100
        ship       0.83      0.82      0.82       100
       truck       0.78      0.79      0.79       100
