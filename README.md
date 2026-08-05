# Credit Risk Analysis & Prediction Dashboard
## 📌 Project Overview
This project focuses on credit risk analysis using SQL, Python, and Power BI.
We built an end-to-end pipeline that starts with raw loan applicant data and ends with an interactive dashboard for stakeholders to monitor loan defaults.
## 🛠️ Tech Stack
- **SQL (PostgreSQL, pgAdmin4)** → Data cleaning, transformations, feature engineering.
- **Python (Pandas, Scikit-learn, XGBoost, Random Forest)** → ML model training & evaluation.
- **Power BI** → Dashboard for visualization & business insights.
## 🔑 Steps Implemented
### 1️⃣ Data Preparation (SQL)
- Imported loan applicant dataset into PostgreSQL.
- Cleaned missing values (median imputation for numeric, mode for categorical).
- Engineered new features: Loan-to-Income Ratio, Employment Category, Age/Income/Interest Rate Bands.
### 2️⃣ Machine Learning (Python)
- Encoded categorical variables using OneHotEncoder.
- Built pipelines with Random Forest and XGBoost.
- Tuned hyperparameters using GridSearchCV.
- Achieved strong performance: Accuracy ~93%, Recall ~75% after tuning XGBoost.
