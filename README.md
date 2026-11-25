# Bank-Loan-Casestudy
Performed Exploratory Data Analysis (EDA) on a banking loan dataset to identify factors influencing loan default risk. Analyzed customer demographics, income, credit, employment, and previous loan history using Python,Pandas,Matplotlib and Seaborn.Built KPIs and visualizations to generate business insights for risk assessment and lending decisions.

# 🏦 Bank Loan Default Risk Analysis

## 📌 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on a banking loan dataset to identify the factors that influence customer loan defaults. The analysis includes data cleaning, missing value treatment, feature engineering, risk segmentation, KPI creation, and business-driven insights using Python.

The objective is to help financial institutions understand customer behavior, identify high-risk applicants, and support better lending decisions through data-driven analysis.

---

## 🎯 Business Problem
Financial institutions face significant losses due to loan defaults. By analyzing customer demographics, income, employment history, previous loan applications, and credit behavior, this project identifies patterns associated with default risk.

---

## 📂 Dataset
The project uses two datasets:

- **application_data.csv** – Current loan application details
- **previous_application.csv** – Historical loan application records

The datasets are merged where required to generate additional business insights.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Understanding
- Dataset exploration
- Data types analysis
- Descriptive statistics
- Missing value analysis
- Duplicate and unique value inspection

### 2. Data Cleaning
- Removed columns with excessive missing values
- Missing value imputation using:
  - Median
  - Mode
  - Business logic
- Converted categorical flags into numerical values
- Corrected negative day-based features

### 3. Feature Engineering
Created new business features including:

- Age (Years)
- Employment Experience (Years)
- Income (Lakhs)
- Credit Amount (Lakhs)
- Income Groups
- Credit Groups
- Employment Groups
- Age Groups
- Credit Ratio
- Loan Amount Categories

### 4. Exploratory Data Analysis
Performed:

- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Target-wise Default Analysis
- Risk Segmentation
- Distribution Analysis
- Pairplots
- Scatter Plots
- Heatmaps

### 5. Business Analysis
Analyzed:

- Default vs Non-default customers
- Occupation-wise default risk
- Employment stability vs default
- Income group risk
- Credit amount risk
- Family size impact
- Loan repayment behavior

### 6. KPI Generation
Calculated business KPIs such as:

- Total Customers
- Default Rate
- Average Loan Amount
- Average Customer Income
- High Risk Customer Count
- EMI Burden Ratio
- Loan Approval Efficiency

---

## 📈 Visualizations

The project includes multiple visualizations such as:

- Histograms
- Boxplots
- Countplots
- Bar Charts
- Pie Charts
- Scatter Plots
- Pairplots
- Correlation Heatmaps
- Risk Comparison Charts

---

## 🔑 Key Insights

- Identified characteristics associated with loan default.
- Employment stability influences repayment behavior.
- Income and credit ratio help identify high-risk applicants.
- Occupation categories show varying default probabilities.
- Credit amount and customer income provide strong indicators for risk segmentation.
- Generated business KPIs for portfolio monitoring.

---

## 📁 Repository Structure

```
├── Bank_Casestudy.ipynb
├── application_data.csv
├── previous_application.csv
├── columns_description.csv
└── README.md
```

---

## 🚀 Future Improvements

- Predictive Machine Learning models
- Interactive Power BI Dashboard
- Customer Risk Scoring System
- Loan Recommendation Engine
- Automated Data Pipeline

---

## 👨‍💻 Author

**Raghav Arzare**

Mechanical Engineer | Data Analytics Enthusiast

- Python
- SQL
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ⭐ Project Highlights

- End-to-end EDA
- Data Cleaning & Preprocessing
- Feature Engineering
- Business KPI Generation
- Customer Risk Analysis
- Banking Domain Analytics
- Business Insight Generation
```