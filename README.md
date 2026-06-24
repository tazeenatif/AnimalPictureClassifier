# AnimalPictureClassifier
Coarse-to-Fine-Grained Image Classification using Traditional Machine Learning, Ensemble Methods and Transfer Learning (with ResNet50)

This project was completed for COMP30027 Machine Learning at the University of Melbourne. The objective was to investigate how feature representation, dimensionality reduction, nonlinear modelling, ensemble learning, and transfer learning influence image classification performance across tasks of varying complexity.

Two classification tasks were explored:

Task 1: Coarse-grained classification of 10 animal categories using handcrafted image descriptors, including colour histograms, HOG-PCA features, and engineered image features.
Task 2: Fine-grained classification of 10 visually similar bird species using transfer learning with a pretrained ResNet50 convolutional neural network.
Methods
Logistic Regression with Mutual Information feature selection
Support Vector Machines (RBF Kernel)
HistGradientBoostingClassifier
Soft Voting Ensemble Learning
Transfer Learning with ResNet50
Principal Component Analysis (PCA)
Cross-Validation and Hyperparameter Optimisation (GridSearchCV)
Results
Task 1 – Animal Classification
Model	Validation Accuracy
Logistic Regression	55.1%
SVM	52.8%
Gradient Boosting	59.6%
Ensemble	60.3%
5-Fold Cross Validation	61.0%

Kaggle Score: 0.61935

Task 2 – Bird Species Classification
Model	Validation Accuracy
SVM	69.0%
Gradient Boosting	78.6%
Ensemble	78.6%

Kaggle Score: 0.8333

Key Technologies

Python • Scikit-Learn • PyTorch • Torchvision • NumPy • Pandas • PCA • ResNet50 • Ensemble Learning • Computer Vision • Machine Learning
