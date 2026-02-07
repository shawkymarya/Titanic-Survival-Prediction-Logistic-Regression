# 🚢 Titanic Survival Prediction using Logistic Regression

This project focuses on predicting passenger survival on the Titanic dataset using **Logistic Regression**.
It demonstrates a complete **machine learning pipeline**, starting from data exploration to model evaluation.

---

## 📌 Project Overview
The goal of this project is to:
- Analyze the Titanic dataset
- Handle missing values and outliers
- Perform feature engineering and encoding
- Address class imbalance using SMOTE
- Train and evaluate a Logistic Regression model

---

## 🧠 Workflow
1. Exploratory Data Analysis (EDA)
2. Missing Values Treatment
3. Feature Engineering (Family Size)
4. Outlier Handling using IQR Capping
5. Feature Encoding:
   - Ordinal Encoding
   - Label Encoding
   - One-Hot Encoding
6. Handling Class Imbalance using SMOTE
7. Feature Scaling (StandardScaler)
8. Model Training (Logistic Regression)
9. Model Evaluation

---

## 📊 Model Performance

| Metric | Score |
|------|------|
| Accuracy | ~81% |
| Precision | ~82% |
| Recall | ~75% |
| F1 Score | ~78% |
| ROC-AUC | Good separation |

---

## 📈 Evaluation Metrics Used
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve & AUC

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 📂 Dataset
- Titanic dataset loaded directly from **Seaborn**

---

## 🚀 Key Highlights
- No data leakage (scaling applied after train-test split)
- Outliers handled using capping instead of removal
- Proper encoding based on feature nature
- Class imbalance handled using SMOTE

---