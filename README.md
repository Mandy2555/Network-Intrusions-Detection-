# Network-Intrusions-Detection-
Machine learning project to detect and classify network intrusions using supervised learning models. Includes binary and multiclass classification based on historical network traffic data.



## 🧠 Project Overview

With the rise in network usage and complexity, the risk of cyber attacks has grown significantly. This project builds a **classification model** to:
- Detect anomalies and attacks (Binary Classification)
- Identify the type of attack (Multiclass Classification)

---

## 📊 Data Description

The dataset consists of 10+ CSV files representing different types of network activities:
- **Normal traffic**
- **Attack types**: Back, Smurf, Neptune, PortSweep, BufferOverflow, etc.

Each record has 41 features:
- **Basic Features**: Duration, protocol, bytes sent/received, etc.
- **Content Features**: Failed logins, root access, etc.
- **Traffic Features**: Connection counts, error rates, etc.

---

## 🎯 Objectives

1. **Binary Classification**: Normal vs Attack
2. **Multiclass Classification**: Identify attack type

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Matplotlib / Seaborn for EDA
- Jupyter Notebook
- Git & GitHub

---

## ✅ Steps Performed

1. Data Collection & Merging
2. Target Variable Creation (Binary + Multiclass)
3. Data Cleaning & Preprocessing
   - Categorical Encoding
   - Feature Scaling
4. Exploratory Data Analysis (EDA)
5. Model Building
   - Logistic Regression, Random Forest, SVM, XGBoost
6. Model Evaluation
   - Confusion Matrix, ROC-AUC, Classification Report
7. Result Summary & Insights

---
