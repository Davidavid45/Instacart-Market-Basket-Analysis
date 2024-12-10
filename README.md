# Instacart Market Basket Analysis: Predicting Product Reorders

## Project Overview
This project applies machine learning and deep learning models to predict product reorders for Instacart's Market Basket dataset. The aim is to create actionable insights for personalized recommendations and inventory management in e-commerce grocery platforms. We implemented and evaluated five predictive models: logistic regression, random forest, gradient boosting, XGBoost, and a deep learning model.

---

## Features of the Project
### 1. **Data Preprocessing**
- Cleaned and handled missing values in raw data.
- Engineered features such as user-product interactions, reorder rates, and temporal patterns.
- Scaled numerical features for improved model performance.

### 2. **Machine Learning Models**
- **Logistic Regression**: Used as a baseline for comparison.
- **Random Forest**: Modeled non-linear feature interactions.
- **Gradient Boosting & XGBoost**: Delivered robust predictions with balanced precision and recall.
- **Deep Learning**: Captured complex patterns with high accuracy and recall.

### 3. **Evaluation Metrics**
- Accuracy, Precision, Recall, and F1-Score were calculated for comprehensive model evaluation.

### 4. **Key Results**
- Deep learning achieved the highest accuracy (90.4%) and recall (63%) for reordered products.
- XGBoost provided robust results with balanced performance and computational efficiency.

---

## Included Files
1. **Instacart_Market_Basket_Analysis_Group4.pdf**  
   - Final report detailing methodology, findings, and recommendations.
2. **Instacart_Basket_Analysis_Project_Group4.ipynb**  
   - Complete Jupyter notebook containing data preprocessing, model building, and evaluation.
3. **Machine_Learning_1.ipynb**  
   - Notebook focused on machine learning model implementations and evaluation.

---

## How to Run the Project
### 1. **Environment Setup**
- Install the required dependencies:
  ```bash
  pip install numpy pandas matplotlib scikit-learn xgboost tensorflow

### 2. Execute the Code
- Run the Jupyter notebooks (.ipynb files) in sequential order for full results.
- Ensure the dataset is loaded correctly before executing.

