# Early_Detection_of_Parkison_Disease
Machine learning project for Parkinson’s disease prediction using biomedical voice data. Applied feature selection (L1, PCA, Chi-Square, Fisher score, dispersion) and SMOTE for imbalanced data. Compared models like SVM, RF, LR, DT, KNN; Random Forest achieved best accuracy (94.8%).
## Project Overview
- This project focuses on predicting Parkinson’s disease using various machine learning algorithms combined with feature selection techniques. The dataset contains biomedical voice measurements of patients, where the goal is to classify whether the patient has Parkinson’s disease.
- The study compares multiple algorithms (Logistic Regression, Decision Tree, Random Forest, Naïve Bayes, SVM, K-Nearest Neighbors) and evaluates the effect of different feature selection and dimensionality reduction techniques.
## Problem Statement
How do different machine learning algorithms (SVM, Random Forest, Logistic Regression, Decision Tree, KNN, Naïve Bayes) perform on Parkinson’s disease datasets when combined with feature selection techniques?
## Techniques Used
### Data Preprocessing
- Handled imbalanced dataset using SMOTE (Synthetic Minority Oversampling Technique).
### Feature Selection & Dimensionality Reduction
- L1 Regularization (Lasso Regression) – Identifies and retains important features by setting irrelevant coefficients to zero.
- PCA (Principal Component Analysis) – Reduced feature dimensionality for improved computation efficiency.
- Chi-Square Test – Selected features based on statistical dependence with the target variable.
- Fisher’s Score – Ranked features by class separability.
- Dispersion Measures – Identified useful features with high discriminative potential.
### Machine Learning Models Tested
- Logistic Regression
- Decision Tree
- Random Forest
- Naïve Bayes
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
## Tools & Libraries
### Programming Language: 
- Python
### Libraries Used:
- pandas, numpy – Data Processing
- scikit-learn – Machine Learning Models & Evaluation
- imblearn – SMOTE for handling imbalances
- matplotlib, seaborn – Data Visualization
## Conclusion
- Random Forest outperformed other models and was the most reliable for Parkinson’s disease prediction.
- Feature selection (especially L1 regularization) significantly improved interpretability and accuracy.
- This study highlights how combining feature engineering + ensemble methods can improve medical diagnosis support tools.
