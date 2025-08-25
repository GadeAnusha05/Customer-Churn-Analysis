📊 Customer Churn Analysis
📌 Project Overview

This project analyzes customer churn data to understand patterns and reasons why customers discontinue services.
The dataset used is Telco Customer Churn, which contains information about customer demographics, services used, payment methods, and whether the customer has churned or not.

The analysis includes:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA) with visualizations

Insights into churn behavior (tenure, contracts, services, payment methods, etc.)

Foundation for building predictive machine learning models

📂 Dataset

The dataset Customer Churn.csv contains the following key columns:

customerID → Unique customer identifier

gender, SeniorCitizen, Partner, Dependents → Demographics

tenure, Contract, InternetService, PhoneService, TechSupport, etc. → Services subscribed

MonthlyCharges, TotalCharges → Billing information

Churn → Target variable (Yes/No)

⚙️ Steps in the Notebook
1. Data Cleaning

Converted "TotalCharges" to numeric

Replaced blanks with 0 (or imputed)

Converted SeniorCitizen from 0/1 → Yes/No

2. Exploratory Data Analysis (EDA)

Churn distribution → Countplot & Pie chart

Demographics vs Churn → Gender, Senior Citizens

Tenure vs Churn → Long-term customers less likely to churn

Contract Type vs Churn → Month-to-month contracts churn the most

Services vs Churn → Security/Tech support reduce churn

Payment Method vs Churn → Electronic check users churn more

Visuals → Countplots, Histograms, Pie charts, Stacked Bar charts

3. Key Insights

26.5% of customers churned

Senior Citizens churn more than younger customers

Short tenure customers are more likely to leave

Month-to-month contracts have the highest churn rate

Customers using Electronic Check payments churn the most

📈 Visualizations

Some of the plots created:

Churn distribution (Countplot + Pie chart)

Gender vs Churn

Senior Citizen vs Churn (Stacked bar with % labels)

Tenure histogram with churn overlay

Contract Type vs Churn

Services (Phone, Internet, TechSupport, etc.) vs Churn

Payment Method vs Churn
