# Project Overview

This project focuses on building and comparing multiple machine learning models to classify breast cancer tumors as malignant or benign using the Breast Cancer dataset from sklearn.
The goal is to evaluate different classification algorithms and identify which model performs best for this dataset.
Dataset Source: sklearn.datasets.load_breast_cancer
Type: Binary classification
Classes:
0 → Malignant
1 → Benign
Features:
30 numerical features (e.g., radius, texture, area, smoothness)
## Preprocessing Steps
- Checked for missing values (none found)
- Applied feature scaling using StandardScaler
Ensures all features have mean = 0 and standard deviation = 1

## The following five classification algorithms were implemented:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

k-Nearest Neighbors (k-NN)

## Model Performance (Accuracy)

Model	Accuracy (approx.)

Logistic Regression	97% – 99%

Decision Tree	92% – 95%

Random Forest	96% – 99%

SVM	97% – 99%

k-NN	95% – 97%

## Results

Best Performing Models: SVM and Random Forest

Lowest Performing Model: Decision Tree
