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
- SHAP summary plot illustrating feature impact distribution across 10% test samples
- SHAP summary plot illustrating feature impact distribution across all misclassified test samples

## Requirements
- pip install -r requirements.txt

## Visualized Features
The repository includes four interactive HTML files generated as part of the feature visualization process (Inside **Visualized_Feature** folder):

| File Name         | Description                                                                 |
|--------------------|------------------------------------------------------------------------------|
| 3D_Scatter.html    | Interactive **3D plot** visualizing feature relationship (days in hospital, heart rate, SBP in relation to outcome) (https://balamuralibt.github.io/XGBoost_Prediction_Task/Visualized_Feature/3D_Scatter.html)|
| PCA.html  | 3D projection of features using **Principal Component Analysis (PCA)**           |
| UMAP.html          | 3D projection of features using **Uniform Manifold Approximation and Projection (UMAP)** |
| t-SNE.html         | 3D projection of features using **t-distributed Stochastic Neighbor Embedding (t-SNE)**   |
| 3D_Scatter_Misclassified.html    | Interactive **3D plot** visualizing feature relationship (days in hospital, heart rate, SBP in relation to outcome) for misclassified cases |
                                                                            

## Data Availability
For privacy reasons, sim_interview_dataset.csv has not been included in this repository.
Kindly contact the author for access to the dataset if required.
