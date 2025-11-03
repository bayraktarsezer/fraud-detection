# 💳 Fraud Detection System

A Data Science project for detecting fraudulent credit card transactions using **Logistic Regression** and **Random Forest**, with data balancing via **SMOTE**.

---

## Overview
This project analyzes credit card transactions to identify fraudulent activity in a highly imbalanced dataset.  
It includes data preprocessing, visualization, model training, and evaluation steps, following an end-to-end data science workflow.

The goal is to build a reliable fraud detection pipeline that can distinguish fraudulent transactions from legitimate ones in real time.

---

## Tech Stack
**Python**, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Imbalanced-Learn, Jupyter Notebook

---

## Key Steps
1. **EDA:** Class distribution, transaction amount and time patterns, correlation heatmap  
2. **Preprocessing:** Feature scaling (`StandardScaler`) and class balancing (`SMOTE`)  
3. **Models:**  
   - Logistic Regression → ROC-AUC: 0.946  
   - Random Forest → ROC-AUC: **0.978**  
4. **Insights:** Most influential features: V14, V12, V4, V11, V10, V17

---

## 📈 Results Summary
| Metric | Logistic Regression | Random Forest |
|--------|---------------------|----------------|
| ROC-AUC | 0.946 | **0.978** |
| Accuracy | 0.97 | **0.99** |
| Recall (Fraud) | 0.91 | 0.82 |

---

