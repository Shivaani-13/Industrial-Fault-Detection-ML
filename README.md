# Industrial Fault Detection ML

## Overview
Developed an end-to-end machine learning pipeline for industrial fault detection using the SECOM semiconductor manufacturing dataset.

## Dataset
- 1567 samples
- 591 sensor features
- Class imbalance: 93:7

## Methodology
- Missing value handling
- Zero-variance feature removal
- Isolation Forest for outlier detection
- SMOTE oversampling
- PCA dimensionality reduction
- KNN, Decision Tree, and SVM classification

## Evaluation Metrics
- Recall
- F1 Score
- Precision-Recall
- AUC-ROC

## Key Results
- Reduced 591 features to 162 principal components
- Retained 95% variance
- Evaluated models using metrics suitable for imbalanced datasets
