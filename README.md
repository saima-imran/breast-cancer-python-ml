# breast-cancer-python-ml
Breast cancer classification using Random Forest — Python. AUC = 0.995, 5-fold cross-validated, n=569. scikit-learn, pandas, seaborn.
# Breast Cancer Classification — Python Analysis
**Author:** Saima Imran  
**Date:** April 2026  
**Language:** Python (pandas, scikit-learn, seaborn, matplotlib)

## Project Overview
Machine learning analysis of breast cancer tumour data using 
the Wisconsin Breast Cancer Dataset (569 patients, 30 features).
This project complements my R-based breast cancer analysis and 
demonstrates Python proficiency in bioinformatics and ML workflows.

## Methods
- Exploratory data analysis with pandas
- PCA dimensionality reduction (44.3% variance in PC1)
- Random Forest classification (5-fold cross-validated)
- ROC curve and feature importance analysis

## Results
- Classification accuracy: 96%
- AUC = 0.995 (5-fold cross-validated)
- Top predictive features: worst area, worst concave points

## Files
- `breast_cancer_analysis.ipynb` — main notebook
- `diagnosis_distribution.png` — patient distribution plot
- `pca_plot.png` — PCA tumour separation
- `roc_curve.png` — ROC curve
- `feature_importance.png` — top 10 features

## Dataset
Wisconsin Breast Cancer Dataset via scikit-learn.  
569 samples | 30 features | 2 classes (Benign/Malignant)
