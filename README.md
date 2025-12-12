# Customer Churn Analysis (Python EDA)

This project analyzes customer churn for a telecom company using Python and exploratory data analysis (EDA).
The goal is to identify customer segments with high churn risk and provide actionable business insights
to improve customer retention.

---

## 📌 Project Objective
- Understand factors driving customer churn
- Identify high-risk customer segments
- Analyze customer behavior, services, and billing patterns
- Provide data-driven recommendations to reduce churn

---

## 📊 Dataset
- Telco Customer Churn Dataset
- Each row represents a customer
- Features include:
  - Demographics (gender, senior citizen, partner, dependents)
  - Account information (tenure, contract type, payment method)
  - Services (internet, phone, streaming, tech support)
  - Billing (monthly charges, total charges)
  - Target variable: **Churn**

---

## 🔍 Analysis Performed
- Data cleaning and preprocessing
- Handling missing values and duplicates
- Encoding categorical variables
- Exploratory Data Analysis (EDA)
  - Churn distribution
  - Numerical features vs churn (tenure, charges)
  - Categorical features vs churn (contract, payment method, internet service)
- Insight extraction and business recommendations

---

## 🔑 Key Insights
- Customers on **month-to-month contracts** have the highest churn rate
- **High monthly charges** are strongly associated with churn
- **Fiber optic** internet users churn more than DSL users
- Customers using **electronic check** payment method churn the most
- **New customers** (low tenure) are at the highest risk of churning
- Senior citizens show slightly higher churn, but it is not a primary driver

---

## 📌 Business Recommendations
- Encourage long-term contracts with discounts and loyalty benefits
- Review pricing strategy for high-bill customers
- Improve service quality for fiber optic users
- Promote automatic payment methods over electronic checks
- Strengthen onboarding and early engagement for new customers

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- GitHub

---

## 📁 Files in Repository
- `customer_churn_analysis.ipynb` → Complete EDA notebook
- Dataset CSV file (optional)

---

## 🚀 Purpose of This Project
This project demonstrates:
- Real-world data cleaning and EDA skills
- Ability to translate data insights into business decisions
- Strong foundation for entry-level Data Analyst roles
