# House Price Prediction Using Boston Housing Dataset  

## Overview  
This project predicts house prices based on various features from the **Boston Housing Dataset**. By utilizing advanced machine learning techniques and data preprocessing, the project builds robust models to ensure high prediction accuracy. Additionally, **SHAP (SHapley Additive exPlanations)** is used for interpreting the best model to understand the contribution of each feature to the predictions.

---

## Features  
- **Data Preprocessing**:  
  - Used **iterative imputations** to handle missing values.  
  - Applied **SMOTE (Synthetic Minority Oversampling Technique)** to handle data imbalance for better predictions.  

- **Machine Learning Models**:  
  - Trained the following models:  
    - **XGBoost**  
    - **Random Forest**  
    - **Linear Regression**  
    - **Decision Tree**  
  - Used **K-Nearest Neighbors (KNN)** for exploratory analysis.  

- **Model Selection**: Evaluated models based on performance metrics to select the best-performing one.  

- **Model Explainability**: Utilized **SHAP** to explain feature importance and their influence on the predictions of the best-performing model.  

---

## How It Works  

1. **Data Preprocessing**:  
   - Missing data is imputed using iterative techniques to maintain data integrity.  
   - SMOTE is applied to address any data imbalance and enhance the model's prediction power.  

2. **Model Training**:  
   - Multiple machine learning models are trained and evaluated on the dataset.  
   - Hyperparameter tuning is performed for optimal model performance.  

3. **Model Evaluation**:  
   - Models are compared using evaluation metrics like RMSE, MAE, and R².  
   - The best-performing model is selected for explainability analysis.  

4. **Model Explainability**:  
   - **SHAP** is used to understand the impact of each feature on the predictions, enabling better decision-making and trust in the model.

---

## Results
Best Model: Random Forest  

Performance Metric:  
- R²: 0.92

Feature Importance (SHAP):
- SHAP analysis revealed that the most critical features influencing house prices are:

  - LSTAT
  - RM
  - CHAS
