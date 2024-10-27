# Breast Cancer Diagnosis Using Support Vector Machine (SVM) with Hyper-Parameter Tuning

This repository contains a machine learning project for classifying breast cancer tumors as benign or malignant based on diagnostic imaging features. The project utilizes the Breast Cancer Wisconsin (Diagnostic) Dataset from Kaggle and implements a Support Vector Machine (SVM) Classifier with hyper-parameter tuning to enhance model performance.

## Project Overview

Breast cancer diagnosis is critical for early intervention and successful treatment. By analyzing diagnostic features, this project aims to accurately classify tumors, assisting in medical decision-making. The SVM algorithm is particularly suitable for this task as it maximizes the margin between classes, making it robust for binary classification.

## Key Features

* Hyper-Parameter Tuning: The SVM model’s performance is optimized through hyper-parameter tuning using GridSearchCV, exploring a range of values for kernel type, regularization parameter (C), and kernel-specific parameters (e.g., gamma).
* Evaluation Metrics: Model performance is assessed using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. An ROC curve is also provided to visualize the model's sensitivity and specificity.
* Data Preprocessing: Data scaling and label encoding are applied to ensure the model’s effectiveness and accuracy.

## Dataset
The dataset includes 569 samples with features derived from images of cell nuclei. Each sample is classified as either Malignant (1) or Benign (0). Key attributes include radius, texture, perimeter, area, and smoothness of the cell nuclei. This dataset allows us to explore key indicators of malignancy and build a robust model for prediction.

##Steps in This Project

* Data Exploration and Preprocessing: Analyzing feature distributions and performing necessary preprocessing steps.
* Model Training: Implementing an SVM classifier with hyper-parameter tuning to select the optimal model configuration.
* Model Evaluation: Using classification metrics and ROC analysis to evaluate model accuracy and performance.
