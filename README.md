# 📊 Customer Churn Prediction – Machine Learning Project

This project was developed as part of **InternForte's Machine Learning Internship (Project 1)**. The goal is to predict customer churn in a telecom dataset using supervised machine learning techniques.

---

## 📌 Project Objectives

- Predict whether a customer will churn (label: 0 or 1).
- Identify key behavioral and financial indicators influencing churn.
- Handle class imbalance using SMOTE.
- Evaluate model performance using precision, recall, F1-score, and accuracy.

---

## 📂 Dataset Summary

- **Size:** ~209,000 rows
- **Target Variable:** `label` (1 = churned, 0 = not churned)
- **Important Features:**
  - `aon` – Age on Network
  - `daily_decr90` – Average daily decrease over 90 days
  - `rental90`, `medianamnt_loans30`, etc.

---

## 🧹 Data Preprocessing

- Removed or imputed missing and negative values
- Encoded categorical feature (`pcircle`)
- Used **SMOTE** to balance imbalanced classes
- Feature scaling and splitting into train-test sets

---

## 🤖 Model Training

- **Model Used:** Random Forest Classifier
- **SMOTE:** Used to handle imbalanced classes before training
- **Evaluation Metrics:**
  - Accuracy: **94%**
  - F1-Score: **0.94**
  - Precision/Recall: Balanced

---

## 📌 Tools & Libraries

- Python
- pandas
- scikit-learn
- imbalanced-learn (SMOTE)
- matplotlib / seaborn

---

## 📈 Results

- Balanced dataset using SMOTE
- High model accuracy on test data
- Key influencing features identified for business decisions

---

## 🏁 How to Run

```bash
pip install -r requirements.txt
# Then run the notebook file
