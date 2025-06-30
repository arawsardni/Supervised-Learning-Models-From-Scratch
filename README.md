# Supervised-Learning-Models-From-Scratch

# 📊 Telco Customer Churn Prediction using Supervised Learning

This project is part of the **Advanced Artificial Intelligence** coursework at Universitas Brawijaya. It focuses on predicting customer churn in the telecommunications industry using supervised learning algorithms. The dataset used comes from [Kaggle's Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn).

## 📌 Project Goals

- Develop machine learning models to predict customer churn.
- Compare the performance of various supervised learning algorithms: Decision Tree, Support Vector Machine (SVM), and Random Forest.
- Implement and evaluate both manual and Scikit-learn versions of selected models.
- Evaluate model performance using metrics: Accuracy, Precision, Recall, and F1-Score.

## 🛠 Tools & Libraries

- Python
- Pandas & NumPy (data manipulation)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (modeling and evaluation)
- Custom implementations of Decision Tree and SVM (from scratch)

## 📈 Methods

### 1. Data Preprocessing
- Handling missing values (e.g. `TotalCharges` with empty string)
- Type conversion and encoding categorical features
- Feature scaling using `RobustScaler`
- Handling class imbalance through stratified train-test split

### 2. Modeling
- **Manual Implementation:**
  - Decision Tree using Gini Index
  - Linear SVM using SGD optimization
- **Scikit-Learn Implementation:**
  - Decision Tree Classifier
  - Support Vector Classifier
  - Random Forest Classifier

### 3. Evaluation
- Confusion Matrix (manual and `sklearn`)
- Accuracy, Precision, Recall, F1-Score (both class-wise and average)

## 🔍 Key Findings

- The dataset is **imbalanced**, with ~26% of customers labeled as churn.
- `Random Forest` performed best overall on the dataset.
- Manual SVM implementation showed competitive results compared to Scikit-learn.
- Manual and library-based models gave useful insights into algorithm behavior and interpretability.

## 👨‍🏫 Authors

- Gaung Taqwa Indraswara (235150207111043)  
- Muhammad Fauzan (235150201111044)  
- Ferrel Destatiananda Edwardo (235150207111044)  
- Muhammad Fatir Zaira (23515020011039)

## 📚 Advisor

- Putra Pandu Adikara, S.Kom., M.Kom.

## 🏫 Institution

Fakultas Ilmu Komputer, Universitas Brawijaya  
Course: Kecerdasan Artifisial Lanjut (Advanced AI)  
Year: 2025
