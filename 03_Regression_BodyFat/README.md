# Body Fat Percentage Prediction

## Overview
Developed a regression model to predict body fat percentage from various body measurements, aiming to identify the key factors influencing body fat and provide interpretable, actionable insights for individuals.

## Data
- **Target variable**: `BodyFat` (body fat percentage)
- **Predictors**: various body measurement variables (e.g., age, weight, height, circumference measurements)

## Approach

**1. Exploratory Data Analysis**
- Examined variable distributions and relationships with body fat percentage using scatter plots, boxplots, and descriptive statistics
- Identified variables most strongly associated with body fat percentage to inform model design

**2. Feature Engineering**
- Applied scaling/transformation where necessary and selected relevant predictors

**3. Regression Modeling**
- Built a baseline multiple regression model and interpreted coefficients to assess each variable's effect on body fat percentage
- Identified the most influential predictors

**4. Model Evaluation**
- Evaluated model performance using R-squared, p-values, and MSE

**5. Regression Assumption Testing**
- Checked linearity, homoscedasticity, independence, and normality of residuals

**6. Model Improvement**
- Based on assumption checks and evaluation results, improved the model through variable transformation, feature selection, polynomial regression, and regularization methods (Ridge, LASSO)

**7. Conclusion & Insights**
- Translated statistical results into practical insights — identifying which body measurements most meaningfully predict body fat percentage and how this could inform personalized health recommendations or fitness-related products/services

## Tech Stack
`Python` `scikit-learn` `statsmodels` `Regression` `Ridge/LASSO`


