# Employee Attrition Prediction – HR Analytics Project

## 📌 Overview
This project analyzes employee data to predict attrition (employee churn) and identify key factors contributing to employee resignation.  
It combines **data analysis, machine learning, and visualization** to provide actionable insights for HR decision-making.

---

## 📊 Dataset
- Source: IBM HR Analytics Employee Attrition Dataset (Kaggle)  
- File: `WA_Fn-UseC_-HR-Employee-Attrition.csv`  
- Contains information on employee demographics, job role, salary, promotions, and attrition status.

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)  
- **XGBoost** – Gradient boosting model  
- **Imbalanced-learn (SMOTE)** – For handling class imbalance  
- **Power BI** – Interactive dashboards & HR metrics visualization  

---

## 🔎 Steps Involved
1. **Data Preprocessing** – Cleaned dataset, encoded categorical features, scaled numeric features.  
2. **Exploratory Data Analysis (EDA)** – Department-wise, salary-band-wise, and role-wise attrition analysis.  
3. **Model Building** – Logistic Regression, Decision Tree, Random Forest, and XGBoost.  
4. **Imbalance Handling** – Applied SMOTE to balance attrition vs non-attrition cases.  
5. **Evaluation** – Confusion matrix, precision, recall, F1-score.  
6. **Feature Importance** – Salary, Job Role, and Years at Company emerged as top predictors.  
7. **Visualization** – Created Power BI dashboard with interactive filters and KPIs.

---

## 📈 Results
- Logistic Regression & Decision Tree worked moderately.  
- **Random Forest**: Accuracy ~80%  
- **XGBoost**: Accuracy ~83% with better precision & recall for attrition cases.  
- Key Insights:
  - Higher attrition in Sales department.  
  - Low salary bands and fewer promotions lead to higher attrition.  
  - Younger employees (20–30 age group) showed higher turnover.  

---

## 📊 Dashboard
A Power BI dashboard was built with:
- KPIs: Total Employees, Attrition Count, Attrition Rate, Average Monthly Income  
- Attrition by Department  
- Attrition by Job Role  
- Attrition by Salary Band  
- Attrition by Age Group  
- Attrition vs Years at Company  
