# 📉 Customer Churn Prediction

> Predicting customer churn using deep learning techniques for proactive customer retention strategies.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

## 🧠 Overview

Customer churn — when a customer stops using a company’s service — is a major concern across industries like telecom, banking, and e-commerce. This project uses a deep learning model (Artificial Neural Network) to predict customer churn based on historical data, enabling businesses to retain customers with timely interventions.

## 📂 Project Structure

├── data/ # Raw and processed datasets ├── notebooks/ # Jupyter notebooks for EDA and model building ├── models/ # Trained model files ├── src/ # Source code and utility scripts ├── README.md # Project documentation ├── requirements.txt # Python dependencies └── churn_predictor.py # Main script for training/prediction

---

## 📊 Dataset

- Source: Public dataset available on [Kaggle](https://www.kaggle.com/)
- Features include:
  - Demographics: Gender, Age, Geography
  - Account info: Tenure, Contract Type, Monthly Charges
  - Label: `Churn` (Yes/No)

---

## ⚙️ Model Details

- Model: Artificial Neural Network (ANN)
- Evaluation Metrics:
  - **Accuracy**: 0.86
  - **Precision**: 0.89
  - **Recall**: 0.96
  - **F1 Score**: 0.92
  - **ROC-AUC**: 0.82

- Techniques:
  - Label Encoding & One-Hot Encoding
  - StandardScaler normalization
  - GridSearchCV & RandomizedSearchCV for hyperparameter tuning
  - Evaluation using Confusion Matrix and ROC Curve

