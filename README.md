# XGBoost_Task – Predictive Modeling

This project demonstrates the use of **XGBoost** for classification on a sample dataset.  
The workflow is implemented in a Jupyter Notebook (`XGBoost_Task.ipynb`).

## Overview
This notebook covers:
- Data preprocessing (loading and encoding categorical values)
- Exploratory analysis and statistical summary of the dataset
- Distribution plots of features with respect to outcome
- Statistical testing of feature associations (Mann–Whitney U for numerical, Chi-square for categorical)
- Dimensionality reduction and visualization using PCA, UMAP, and t-SNE
- Model training with XGBoost, including hyperparameter optimization via randomized search with stratified cross-validation
- Model evaluation (Precision, Recall, F1-score) and balanced accuracy distribution using repeated stratified cross-validation
- Feature importance analysis and visualization using XGBoost’s gain metric

## Requirements
- pip install -r requirements.txt
