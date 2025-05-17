# Diabetes Risk Prediction using MLflow

This project implements a machine learning pipeline for predicting diabetes risk using Logistic Regression. The full ML lifecycle is managed with MLflow, including experiment tracking, parameter tuning, and model logging. The domain is healthcare, and the dataset includes individual health and lifestyle indicators.

## 🧠 What This Project Includes

- Logistic Regression model with GridSearchCV tuning  
- One-hot encoding for categorical features  
- Train/test split with performance evaluation  
- MLflow tracking of:  
  - Model parameters  
  - Accuracy and F1 metrics  
  - Trained model artifact  
- **Dependency management using Poetry**

## 🚀 How to Run (with Poetry)

1. Clone the repository  
   `git clone https://github.com/zhradre/mlflow-diabetes.git`

2. Navigate to the project folder  
   `cd mlflow-diabetes`

3. Install dependencies  
   `poetry install`

4. Activate the virtual environment  
   `poetry shell`

5. Run the training notebook  
   Open `notebooks/01_model_training.ipynb` and run all cells

6. (Optional) Start MLflow UI  
   `mlflow ui`

## 📌 Notes

- Dataset is located at `data/diabetes_risk_dataset.csv`  
- Only **Logistic Regression** is used, tuned with `GridSearchCV`  
- MLflow experiment is named `"Diabetes Risk Prediction"`  
