# Heart Disease Prediction

## Overview
Heart disease remains one of the leading causes of death worldwide, making early detection and risk prediction critical for preventive care. This project builds classification models to predict the likelihood of heart disease based on patient clinical data, and compares the performance of multiple models.

## Data
- **Source**: UCI Machine Learning Repository - Heart Disease Prediction Dataset
- **Preprocessing**: Missing value and outlier treatment, categorical encoding (one-hot / label encoding), train/test split (80/20), and feature scaling

## Approach

**1. Exploratory Data Analysis (EDA)**
- Examined descriptive statistics and distributions of each variable
- Researched the clinical meaning of each variable to inform modeling decisions

**2. Modeling**
Applied and compared four classification models:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

Hyperparameter tuning and class imbalance handling were considered during training.

**3. Model Evaluation**
- Compared performance using Accuracy, Precision, Recall, and F1-score
- Selected the best-performing model based on combined metrics

**4. Feature Importance Analysis**
- Logistic Regression: identified key variables via regression coefficients
- Decision Tree / Random Forest: identified key variables via feature importance
- Interpreted top predictive features from a clinical/medical perspective

## Results & Insights
- Comparative performance results across the four models and rationale for the selected model
- Clinical interpretation of the most predictive features
- Practical directions for applying the prediction model

## Tech Stack
`Python` `scikit-learn` `pandas` `matplotlib/seaborn`

