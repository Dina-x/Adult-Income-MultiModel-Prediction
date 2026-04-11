# Adult Income Analysis: Multi-Model Prediction & Clustering 💰

## Project Overview
This project focuses on analyzing census data to predict whether an individual's income exceeds $50K per year. It showcases a comprehensive machine learning workflow, comparing traditional statistical models with advanced algorithms and exploring data patterns through unsupervised learning.

## Methodology & Implementation

### 1. Supervised Learning (Classification)
We implemented and evaluated multiple classification models to find the most accurate predictor:
* **Linear & Probabilistic Models:** Logistic Regression and Gaussian Naive Bayes were used as baseline classifiers.
* **Advanced Models:** Support Vector Machine (SVM) with optimized hyperparameters to handle non-linear relationships in demographic data.

### 2. Unsupervised Learning & Dimensionality Reduction
To understand the underlying structure of the census data, we applied:
* **K-Means & Hierarchical Clustering:** Grouping individuals into clusters based on occupation, education, and age.
* **Principal Component Analysis (PCA):** Reducing the dataset's dimensionality for better visualization and more efficient computation.

## Conclusion & Final Insights

* Model Performance: Logistic Regression emerged as the best overall classifier due to its high accuracy and stability. However, RBF SVM proved superior in identifying the minority class (`>50K`) more effectively.
* Evaluation Basis: Model reliability was validated using Confusion Matrices and ROC-AUC for supervised learning, and Silhouette Scores to ensure distinct and meaningful clusters in unsupervised learning.
* Data Visualization: Through Seaborn and Matplotlib, complex patterns were simplified using Heatmaps and PCA 2D plots, revealing that education and occupation are the strongest predictors of income level.

## Tech Stack
* **Language:** Python 
* **Libraries:** Scikit-learn, Pandas, NumPy, SciPy, Matplotlib, Seaborn.
