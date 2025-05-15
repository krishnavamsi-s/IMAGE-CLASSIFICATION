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

##OUTPUT
                  precision    recall  f1-score   support

    airplane       0.84      0.72      0.77      1000
  automobile       0.96      0.70      0.81      1000
        bird       0.66      0.55      0.60      1000
         cat       0.62      0.45      0.52      1000
        deer       0.60      0.77      0.68      1000
         dog       0.61      0.70      0.65      1000
        frog       0.79      0.80      0.79      1000
       horse       0.74      0.81      0.78      1000
        ship       0.77      0.89      0.82      1000
       truck       0.77      0.86      0.81      1000

    accuracy                           0.73     10000
   macro avg       0.73      0.73      0.72     10000
weighted avg       0.73      0.73      0.72     10000
