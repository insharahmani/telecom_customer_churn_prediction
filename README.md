# 📞 Telecom Customer Churn Prediction

In today's competitive telecom industry, retaining customers is more important than ever. Customer churn — when users switch to another provider — can significantly impact a company's revenue.  
This project builds a **predictive model** to identify customers likely to leave based on their behavior, usage patterns, and demographics.  
By leveraging data insights and machine learning, telecom companies can act proactively to improve **customer retention** and reduce churn.

---

## 🗂️ Table of Contents
- [Problem Statement](#problem-statement)
- [Objective](#objective)
- [Methodology](#methodology)
- [Data Insights](#data-insights)
- [Power BI Visuals](#power-bi-visuals)
- [Key Findings](#key-findings)
- [References](#references)
- [Usage Instructions](#usage-instructions)
- [Running the Project](#running-the-project)
- [Deployment Steps](#deployment-steps)

---

## 💡 Problem Statement
In the fast-evolving telecommunications sector, customers can easily switch providers.  
**Churn rate**, the percentage of customers who leave a service, directly affects profitability.  

The project aims to:
- Analyze customer behavior and service usage.
- Identify churn drivers.
- Build predictive models for early churn detection.

Understanding churn helps telecoms **target at-risk customers**, improve satisfaction, and optimize retention strategies.

---

## 🎯 Objective
The main goal is to **develop a machine learning model** that classifies customers as potential churners or loyal customers.

### Dataset Overview:
- **Attributes:** customerID, gender, SeniorCitizen, Partner, Dependents, tenure, phone/internet services, contract type, payment methods, monthly & total charges.
- **Target Variable:** `Churn` (Yes/No)

### Analytical Workflow:
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Training (Logistic Regression, Random Forest, Gradient Boosting)  
- Evaluation (Accuracy, Precision, Recall, ROC-AUC)

---

## 🧠 Methodology

### 1. Data Collection & Preparation
- Combined demographic, contract, and billing data.
- Handled missing values and encoded categorical variables.

### 2. Exploratory Data Analysis (EDA)
- Visualized churn distribution by gender, contract type, and tenure.
- Identified strong churn indicators like **month-to-month contracts**, **high charges**, and **no tech support**.
- Used **Power BI** for interactive visual dashboards.

### 3. Predictive Modeling
- Built and tuned ML models: Logistic Regression, Random Forest, Gradient Boosting.
- Compared performance metrics and selected the best model.

### 4. Power BI Visualization
- Designed dashboards to visualize churn trends, customer demographics, and feature importance.

---

## 📊 Data Insights

| Feature Type | Description |
|---------------|-------------|
| **Categorical Features** | Gender, Contract Type, Payment Method, Internet Service |
| **Numerical Features** | Tenure, Monthly Charges, Total Charges |
| **Target Variable** | `Churn` |
| **Top Correlations** | Month-to-month contract, low tenure, no online security |

---

## 📈 Power BI Visuals

### 🔹 Overview Dashboard
Displays churn rate, customer segments, and contract distribution.

### 🔹 Detailed Insights
Analyzes churn across demographics, service usage, and billing patterns.

🔗 *(You can include a Power BI link or screenshot here)*

---

## 🧩 Key Findings
- **High-Risk Segments:** Customers with month-to-month contracts and high monthly charges.  
- **Retention Opportunities:** Offer discounts or better service bundles to long-term users.  
- **Revenue Impact:** Quantified potential losses from churned customers and forecasted recovery through retention strategies.

---

## 📚 References
- [Understanding Customer Churn Rate](https://www.investopedia.com/terms/c/churnrate.asp)  
- [Customer Retention Strategies](https://hbr.org/topic/customer-retention)  
- [Telco Churn Dataset on Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## ⚙️ Usage Instructions

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/Telecom-Customer-Churn-Prediction.git](https://github.com/insharahmani/telecom_customer_churn_prediction)
cd Telecom-Customer-Churn-Prediction
### 2. Install Dependencies
```bash
pip install -r requirements.txt
3. Load Dataset

Load the dataset in Python or Power BI for analysis and model training.

4. Train and Evaluate Model

Run Jupyter Notebook or Python script to train the churn prediction model.
🚀 Running the Project

To run the Flask app locally:

python app.py


Then open your browser and go to:

http://127.0.0.1:5000/


Enter customer details and view churn predictions instantly.

🌍 Deployment Steps

Choose a hosting platform (Heroku / AWS / Azure / PythonAnywhere).

Create an account and upload your project files.

Add required configuration and dependency files.

Deploy the app and access it through the provided URL.
