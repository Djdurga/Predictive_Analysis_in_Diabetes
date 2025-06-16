# 🩺 Predictive Analysis in Diabetes using Logistic Regression

## 📌 Project Overview

This project applies **Logistic Regression** to predict diabetes in patients using the **Pima Indians Diabetes Dataset**. It demonstrates the full data science workflow — from data imputation and EDA to model training, evaluation, and extracting insights.

---

## 🎯 Objective

To build a binary classification model that predicts whether a patient has diabetes (`Outcome: 1`) or not (`Outcome: 0`) using key health indicators such as glucose levels, BMI, insulin levels, and age.

---

## 🧪 Dataset Details

- **Source**: [Kaggle - Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Total Records**: 768
- **Target Feature**: `Outcome` (0 = No Diabetes, 1 = Diabetes)
- **Attributes**:
  - Pregnancies  
  - Glucose  
  - BloodPressure  
  - SkinThickness  
  - Insulin  
  - BMI  
  - DiabetesPedigreeFunction  
  - Age  

---

## 📈 Workflow Summary

1. **📥 Data Import & Exploration**
   - Load dataset using pandas
   - Check structure, shape, missing or zero values

2. **🧹 Data Cleaning**
   - Impute zero values in `Glucose`, `BloodPressure`, `Insulin`, `BMI`, etc.

3. **📊 Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Correlation matrix
   - Visualizations with Seaborn & Matplotlib

4. **⚙️ Model Building**
   - Logistic Regression with Scikit-learn
   - Train-test split

5. **📉 Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC-AUC Curve

---

## 🛠 Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Repository Structure

