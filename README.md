# 📊 VIDEO-GAME-SALES-PREDICTION-USING-MACHINE-LEARNING-
Machine learning-driven predictive analysis of global video game sales based on factors like platform, genre, publisher, and release year. Includes data preprocessing, exploratory analysis, feature engineering, and model comparison. Developed for MSc Data Science dissertation project.

---

## 🎯 Objectives
- **Predict Video Game Sales** 
Leverage machine learning algorithms to forecast global sales trends using historical video game data.

- **Identify Key Influencing Factors**
Determine which attributes (platform, genre, regional sales patterns) significantly impact game sales performance.

_**Optimize Model Performance**
Compare and tune multiple models to achieve the highest possible prediction accuracy.

---

## 🛠️ Key Features
### 1. Data Processing & Cleaning
- Collected video game sales data (16,598 records) from Kaggle and VGChartz (1980–2020).
- Managed missing values via imputation and elimination.
- Encoded categorical variables with Label Encoding.
- Applied feature scaling for numerical stability.

### 2. Exploratory Data Analysis (EDA)
- Visualized sales distributions, genre breakdowns, and platform sales trends using histograms, scatter plots, and correlation matrices.
- Assessed feature relationships with target variable (Global Sales) via correlation heatmaps.

### 3. Machine Learning Model Development
- Linear Regression: Baseline predictive model.
- Decision Tree: Non-linear model with hyperparameter tuning (max_depth, min_samples_split).
- Random Forest: Ensemble method with feature importance visualization.
- Gradient Boosting: Best performer with R² = 0.96 and MSE = 1.15.
- Performed cross-validation and GridSearchCV hyperparameter optimization for all models.

### 4. Model Comparison & Evaluation
- Evaluated models using MAE, MSE, and R² metrics.
- Gradient Boosting achieved the highest accuracy.
- Generated residual plots and prediction vs. actual value graphs for performance assessment.

---

## 📊 Summary
This project demonstrates how machine learning techniques can effectively forecast video game sales and support strategic decision-making in the gaming industry. Through rigorous data preprocessing, feature selection, model building, and optimization, it highlights key factors influencing sales outcomes while delivering actionable insights for developers, marketers, and investors.

---
