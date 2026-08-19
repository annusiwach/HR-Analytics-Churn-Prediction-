# HR-Analytics-Churn-Prediction-
# 📊 HR Analytics: Employee Churn & Predictive Risk Dashboard

An end-to-end data science and business intelligence project designed to analyze employee attrition, identify key turnover drivers using machine learning, and deliver actionable retention strategies through an interactive Power BI dashboard.

---

## 🎯 Project Overview

Employee turnover creates substantial operational and financial costs for organizations. This project builds a complete analytical pipeline—moving from raw HR data preprocessing and statistical exploratory analysis to predictive modeling and executive dashboarding.

### **Key Objectives**
* Identify the primary workforce metrics driving employee attrition.
* Build and evaluate a Machine Learning classifier to predict high-risk churn candidates.
* Deliver an executive-ready **Power BI Dashboard** enabling HR leaders to inspect high-level KPIs and target individual at-risk employees.

---

## 🛠️ Tech Stack & Tools

* **Programming & Libraries:** Python (Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib)
* **Data Science Environment:** Jupyter Notebooks (Anaconda Distribution)
* **Machine Learning Models:** Random Forest Classifier / Logistic Regression
* **Business Intelligence:** Power BI Desktop (DAX, Data Modeling, Custom Visualization)
* **Version Control:** Git & GitHub

---

## 📁 Repository Structure

```text
├── data/
│   ├── raw_employee_data.csv            # Original uncleaned dataset
│   ├── Cleaned_Employee_HR.csv          # Preprocessed data used for modeling & Power BI
│   └── High_Risk_Employees_Action_List.csv # Scored roster of at-risk employees (>70% risk)
├── notebooks/
│   ├── 01_data_cleaning.ipynb           # Null handling, feature engineering & transformations
│   ├── 02_eda_analysis.ipynb            # Correlation analysis & visual distribution checks
│   └── 03_model_building.ipynb          # Model training, hyperparameter tuning & evaluation
├── dashboards/
│   └── HR_Analytics_Dashboard.pbix      # Power BI report file
├── assets/
│   ├── executive_overview.png           # Dashboard Screenshot: Page 1
│   └── predictive_risk_roster.png       # Dashboard Screenshot: Page 2
└── README.md                            # Project Documentation

```

## 💡 Key Insights & Findings
Workload & Burnout: Employees logging high average monthly hours (\ge 250 hours) paired with low satisfaction scores showed the highest churn probability.
Lack of Career Progression: Over 98% of employees who left received zero promotions within the last 5 years.
Tenure Vulnerability: Attrition peaks significantly among employees with a 3-to-5 year tenure.
Compensation Sensitivity: The vast majority of attrited staff fell into the lower and medium salary tiers.

## 📊 Dashboard Overview
The interactive Power BI solution features a high-contrast executive theme organized into two target views:
1. Executive Overview
Focuses on macro-level workforce health, attrition trends, salary tier breakdowns, burnout scatter plots, and department-level turnover rates.
2. Predictive Risk Roster
An operational view filtering for high-probability churn candidates (>70\% probability score), highlighting individual employee IDs, satisfaction levels, evaluation metrics, and calculated risk scores formatted with dynamic conditional color indicators.

## 🚀 How to Run & Reproduce
1. Environment Setup
Clone the repository and install the required dependencies:
https://github.com/annusiwach/HR-Analytics-Churn-Prediction-
2. Execute Notebooks
Run the Jupyter notebooks in order within the notebooks/ directory:
01_data_cleaning.ipynb
02_eda_analysis.ipynb
03_model_building.ipynb
3. View Dashboard
Open dashboards/HR_Analytics_Dashboard.pbix in Power BI Desktop to interact with the visualizations and explore dynamic slicers.

## 📈 Impact & Business Value
By shifting HR operations from reactive exit interviews to proactive risk identification, this analytics pipeline empowers organizations to:
Target retention budgets toward high-value, high-risk personnel.
Address systemic organizational issues such as burnout and stagnant career progression.
Protect key institutional knowledge and reduce costly hiring cycles.
