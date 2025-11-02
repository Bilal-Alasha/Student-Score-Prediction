# 🎓 Student Score Prediction 

This project predicts students' **exam scores** based on various academic, personal, and social factors such as study hours, sleep, attendance, and parental involvement.  
It demonstrates the full machine learning workflow — from **data cleaning** to **model training**, **evaluation**, and **visualization** — using Python.

---

## 🧠 Project Overview

- **Goal:** Predict the final exam score of a student based on multiple input features.
- **Dataset:** [Student Performance Factors (Kaggle)](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)  
- **Tech Stack:**  
  - Python  
  - Pandas  
  - Matplotlib  
  - Scikit-learn  

---



## 🧹 Data Preprocessing

1. **Handled missing values** using the most frequent (mode) value.  
2. **Scaled numeric columns** using `StandardScaler`.  
3. **Encoded categorical columns** using `OneHotEncoder`.  
4. Combined preprocessing and model training into a unified **Scikit-learn Pipeline** to prevent data leakage.

---

## 🧮 Models Implemented

| Model Type | Description |
|-------------|--------------|
| **Linear Regression** | Baseline model for predicting scores. |
| **Polynomial Regression** | Captures potential nonlinear relationships between features. |

---

## 📊 Evaluation Metrics

- **R² Score:** Measures how well predictions fit the actual data.  
- **RMSE (Root Mean Squared Error):** Measures the average prediction error.  

Both metrics are printed after model evaluation for easy comparison.

---

## 🧰 How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Bilal-Alasha/Student-Score-Prediction
cd Student-Score-Prediction
pip install -r requirements.txt
pip install pandas matplotlib scikit-learn
jupyter notebook student_performance.ipynb
