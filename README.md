# Bank Loan Analytics & Default Prediction

## Project Overview 📊

This project is a comprehensive solution combining **business intelligence dashboards** and **predictive machine learning models** to analyze and forecast loan portfolio risk for a USA-based bank.  

It aims to provide actionable insights on loan trends, portfolio health, and proactively predict defaults to guide risk mitigation.

---

## Key Features & KPIs 📈

### Dashboard & EDA

* **Total Loan Applications, Funded Amount, and Amount Received**: Track MTD and MoM changes.
* **Loan Quality Analysis**: Classify loans into Good (Fully Paid/Current) vs Bad (Charged Off).
* **Trend Analysis**: Monthly loan trends and regional analysis by state.
* **Borrower Insights**: Employment length, home ownership, and loan purpose analysis.
* **Visualizations**: Line charts, bar charts, donut charts, tree maps, and detailed grids.

### Predictive Modeling

* **Dataset**: 37K+ loans with 14+ features including numeric and categorical variables.
* **Data Preprocessing**: Duplicate removal, missing value imputation, encoding (ordinal/one-hot), feature scaling, SMOTE for class balancing, log transforms for skewed features.
* **Models Built**:  
  - Logistic Regression  
  - Tree-based Models (Random Forest, XGBoost, LightGBM)  
  - Time-series enhanced models incorporating issue and credit pull dates.
* **Performance**: Tree models achieved **91% accuracy**; key predictors include `int_rate`, `term`, and `loan_amount`.
* **Feature Engineering**: Derived numeric and categorical features from loan dates and borrower info to improve prediction accuracy.

---

## Technical Stack 💻

* **Data Sources**: SQL Server (loan records)
* **ETL & Analysis**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM)
* **Business Intelligence**: Power BI for interactive dashboards
* **Machine Learning**: Regression, Tree Models, Time-series forecasting
* **Version Control**: GitHub

---

## Repository Structure 🗂️

