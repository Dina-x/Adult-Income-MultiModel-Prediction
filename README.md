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

## Key Technical Skills
* **Feature Engineering:** Handling categorical variables and scaling numerical features using `StandardScaler`.
* **Model Evaluation:** Using Confusion Matrices, ROC Curves, and Precision-Recall metrics to ensure model reliability.
* **Data Visualization:** Extensive use of `Seaborn` and `Matplotlib` for exploratory data analysis (EDA).
## Conclusion
Through rigorous experimentation with both supervised and unsupervised learning techniques, the project yielded the following insights:
• Best Performing Model: Logistic Regression emerged as the top-performing classifier, demonstrating the highest overall accuracy and a more balanced confusion matrix compared to other models.
• Model Comparison: While SVM (RBF Kernel) showed superior capability in identifying the minority class (>50K), Gaussian Naive Bayes was less effective due to a high number of false positives.
• Data Insights: The unsupervised learning phase (K-Means & PCA) successfully captured underlying demographic clusters, proving that high-income patterns are strongly correlated with specific education and occupation features.

## Tech Stack
* **Language:** Python 
* **Libraries:** Scikit-learn, Pandas, NumPy, SciPy, Matplotlib, Seaborn.
