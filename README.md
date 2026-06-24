# 🦁 AnimalPictureClassifier

**Coarse-to-Fine-Grained Image Classification using Traditional Machine Learning, Ensemble Methods, and Transfer Learning (ResNet50)**

## Overview

This project was completed for **COMP30027 Machine Learning** at the **University of Melbourne**.

The objective was to investigate how **feature representation**, **dimensionality reduction**, **nonlinear modelling**, **ensemble learning**, and **transfer learning** influence image classification performance across tasks of varying complexity.

Two image classification tasks were explored:

### Task 1: Coarse-Grained Animal Classification

Classification of 10 animal categories using handcrafted image descriptors, including:

* Colour histogram features
* HOG-PCA features
* Engineered image descriptors

### Task 2: Fine-Grained Bird Species Classification

Classification of 10 visually similar bird species using transfer learning with a pretrained **ResNet50** convolutional neural network.

---

## Methods

### Traditional Machine Learning

* Logistic Regression
* Support Vector Machine (RBF Kernel)
* HistGradientBoostingClassifier

### Feature Engineering & Selection

* Mutual Information Feature Selection
* Principal Component Analysis (PCA)
* Feature Scaling and Preprocessing

### Ensemble Learning

* Soft Voting Ensemble Classifier
* Weighted Model Combination

### Deep Learning & Transfer Learning

* Pretrained ResNet50 Feature Extraction
* ImageNet Weights
* Deep Feature Embeddings

### Model Evaluation

* Stratified Train/Test Split
* 5-Fold Cross Validation
* GridSearchCV Hyperparameter Optimisation

---

## Results

### Task 1 – Animal Classification

| Model                   | Validation Accuracy |
| ----------------------- | ------------------- |
| Logistic Regression     | 55.1%               |
| SVM                     | 52.8%               |
| Gradient Boosting       | 59.6%               |
| Ensemble                | 60.3%               |
| 5-Fold Cross Validation | 61.0%               |

**Kaggle Score:** `0.61935`

---

### Task 2 – Bird Species Classification

| Model             | Validation Accuracy |
| ----------------- | ------------------- |
| SVM               | 69.0%               |
| Gradient Boosting | 78.6%               |
| Ensemble          | 78.6%               |

**Kaggle Score:** `0.8333`

---

## Key Findings

* Traditional machine learning models performed reasonably well on coarse-grained animal classification.
* Gradient Boosting consistently outperformed Logistic Regression and SVM by capturing nonlinear feature interactions.
* Transfer learning using pretrained ResNet50 features significantly improved performance on fine-grained bird species recognition.
* PCA reduced feature dimensionality while preserving most of the information contained in the deep feature embeddings.
* Ensemble methods provided modest improvements in model robustness and generalisation.

---

## Technologies

* Python
* Scikit-Learn
* PyTorch
* Torchvision
* NumPy
* Pandas
* PCA
* ResNet50
* Ensemble Learning
* Computer Vision
* Machine Learning

---

## Repository Structure

```text
AnimalPictureClassifier/
│
├── Task1/
│   ├── data/
│   ├── notebooks/
│   └── models/
│
├── Task2/
│   ├── data/
│   ├── notebooks/
│   └── models/
│
├── report/
├── requirements.txt
└── README.md
```

---

## Author

**Tazeen Atif**
Bachelor of Science (Data Science)
The University of Melbourne
