# Predict-Employee-Attrition

This project focuses on predicting whether an employee will leave a company using machine learning models trained on the **IBM HR Analytics Employee Attrition & Performance** dataset. Along with building accurate classifiers, this project provides explainable insights using SHAP to guide HR teams in developing effective retention strategies.

---

## 📁 Dataset

- **Source**: [IBM HR Analytics Employee Attrition & Performance Dataset on Kaggle]
- The dataset contains various employee-related features such as job satisfaction, environment satisfaction, age, overtime, salary, years at company, etc., with the target variable `Attrition`.

---

## 📌 Project Objective

- To build and evaluate machine learning models that predict employee attrition.
- To perform Exploratory Data Analysis (EDA) to identify key factors affecting attrition.
- To use model explainability tools (SHAP) to derive actionable business insights for HR.

---

## 🔧 Tools and Technologies Used

- **Google Colab** (for development)
- **Python**
- **Pandas, NumPy, Matplotlib, Seaborn** (for EDA and preprocessing)
- **Scikit-learn** (for model training and evaluation)
- **SHAP** (for model interpretability)
- **Random Forest, Logistic Regression** (classification models)

---

## 📊 Steps Performed

### 1. Exploratory Data Analysis (EDA)
- Analyzed distributions of key features like Age, Job Role, Environment Satisfaction, and Overtime.
- Compared feature distributions for employees who left vs. stayed.
- Identified strong indicators of attrition, e.g., **OverTime**, **Job Satisfaction**, and **Years at Company**.

### 2. Data Preprocessing
- Encoded categorical variables
- Normalized/standardized features where necessary
- Handled class imbalance using techniques such as class weighting or SMOTE (if applied)

### 3. Model Training & Evaluation
- Trained and tested two classification models:
  - **Logistic Regression**
  - **Random Forest Classifier**
- Evaluated using metrics: **Accuracy, Precision, Recall, F1-Score, ROC-AUC**

### 4. Model Explainability
- Used **SHAP (SHapley Additive exPlanations)** to understand the impact of each feature on model predictions.
- Visualized feature importance and individual predictions.

---

## ✅ Results

- **Best Model**: Random Forest Classifier
- **Top Features Influencing Attrition**:
  - OverTime
  - Job Role
  - Environment Satisfaction
  - Years at Company
  - Age

---

## 💡 Actionable HR Retention Strategies

Based on insights from EDA and SHAP:

- **Manage Overtime**: High overtime frequency significantly increases attrition risk. Consider limiting overtime or compensating employees fairly.
- **Monitor Satisfaction Levels**: Employees with low job and environment satisfaction are more likely to leave. Regular satisfaction surveys and interventions are recommended.
- **Career Progression**: Provide growth opportunities and role rotations for mid-tenure employees (3–5 years), who are at higher risk of attrition.
- **Custom Retention Plans**: Tailor strategies based on employee roles, especially for high-risk job roles like Sales Executive and Laboratory Technician.

---
