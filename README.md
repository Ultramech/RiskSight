# RiskSight: Credit Risk Analysis & Prediction Dashboard
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
- Generated predictions + default probabilities for new applicants.
### 3️⃣ Dashboard (Power BI)
#### A. Power BI (Modeling & Visualization)
- Designed an **interactive Credit Risk Dashboard** with slicers for Loan Intent, Loan Grade, and Income Range.
#### B. Business Insights
- **Good Loans %:** 78.18% | **Default Rate:** 22%
- **Expected Loss:** 8.16M | **Total Loan Amount at Risk:** 7M
## 🚀 How to Run
1. Clone this repo.
2. Load the SQL scripts in PostgreSQL to clean & prep data.
3. Run model_training.ipynb in Python to train & evaluate models.
4. Open the Power BI file (Loan Defaulters Final.pbix) to interact with the dashboard.
## 📌 Next Steps (Future Improvements)
- Deploy ML model as a Flask API for real-time scoring.
- Connect API to Power BI for live scoring dashboards.
- Add survival analysis for loan tenure risk.
