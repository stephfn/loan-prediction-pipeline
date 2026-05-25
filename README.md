# Loan Prediction Pipeline with KNN and GridSearchCV

## Overview

This project explores machine learning classification techniques for predicting loan approval outcomes using financial and applicant data. The workflow includes preprocessing, feature engineering, pipeline construction, hyperparameter tuning, and model evaluation using scikit-learn.

A K-Nearest Neighbors (KNN) classifier was developed using a preprocessing pipeline that combined MinMax scaling with supervised machine learning classification techniques.

---

## Techniques Used

- K-Nearest Neighbors (KNN)
- scikit-learn Pipelines
- GridSearchCV Hyperparameter Tuning
- MinMax Scaling
- Dummy Variable Encoding
- Missing Data Handling
- Train/Test Split
- Classification Accuracy Evaluation

---

## Dataset

The dataset consisted of loan applicant information, including demographic and financial variables used to predict loan approval status.

Categorical variables were transformed into numerical features using dummy variable encoding before model training.

---

## Objective

The goal of this project was to evaluate how preprocessing pipelines and hyperparameter tuning influence classification model performance in loan approval prediction tasks.

---

## Project Workflow

1. Load and inspect loan dataset
2. Remove unnecessary features and missing records
3. Encode categorical variables into numerical format
4. Split dataset into training and testing sets
5. Build preprocessing and modeling pipeline
6. Apply MinMax scaling within the pipeline
7. Train baseline KNN classifier
8. Perform GridSearchCV hyperparameter tuning
9. Evaluate model accuracy on test data

---

## Key Findings

- Machine learning pipelines simplified preprocessing and modeling workflows by combining scaling and classification into a single reusable structure.
- MinMax scaling improved KNN performance by standardizing feature ranges for distance-based classification.
- GridSearchCV identified improved hyperparameter settings compared to the baseline model.
- Proper preprocessing and feature encoding significantly influenced classification accuracy.

---

## Tools and Libraries

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

---

## Repository Contents

```text
loan-prediction-pipeline/
│
├── README.md
└── loan_prediction_pipeline.ipynb
```

---

## Author

Stephanie Nord  
Master’s Student in Data Science
