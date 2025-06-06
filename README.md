# Telco Customer Churn Dashboard

An end-to-end data analytics project focused on uncovering patterns behind customer churn using a real-world telecom dataset. The final result is a professional Tableau dashboard that highlights churn behavior across customer segments.

---

## Problem Statement

Customer churn is a major concern for telecom providers. This project aims to analyze which factors (contract type, payment method, tenure, and monthly charges) lead to higher churn and how companies can take proactive action.

---

## Dataset

- Source: IBM Telco Customer Churn dataset ([Kaggle link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn))
- 7,043 rows × 21 columns
- Key fields:
  - `tenure`, `MonthlyCharges`, `TotalCharges`
  - `Contract`, `PaymentMethod`, `InternetService`, `Churn`

---

## Data Cleaning

Performed using Python in Google Colab:
- Removed duplicates
- Converted `TotalCharges` from string to float
- Filtered missing values
- Created new feature: `TenureGroup`
- Encoded binary fields (`Churn`, `Partner`, etc.) to 1/0

▶ View cleaning script: [`data_cleaning.ipynb`](./data_cleaning.ipynb)

---

## Dashboard Features

![Dashboard Screenshot](./dashboard_screenshot.png)

Interactive Tableau dashboard includes:
- **Churn Breakdown** (Yes/No)
- **Churn by Contract Type**
- **Churn by Tenure Group**
- **Churn by Payment Method**
- **Monthly Charges Histogram**
- Interactive filters (Gender, Internet Service, Senior Citizen)

▶View Live Dashboard: [Tableau Public Link](https://public.tableau.com/app/profile/sai.niketh.mulakala/viz/p1_17491715393480/Dashboard1)

---

## Key Insights

- 📉 Customers on **month-to-month** contracts have highest churn
- 🧾 **Electronic check** is the most churn-prone payment method
- 📈 Customers with **high monthly charges** and **low tenure** are at the highest risk
- 📊 Two-year contract customers are least likely to churn

---

## Tools Used

- Tableau Public
- Google Colab (Python, Pandas)
- GitHub

---

## Author

**Sai Niketh Mulakala**  
📍 M.S. Business Analytics — University of Texas at Dallas  
🔗 [LinkedIn](https://www.linkedin.com/in/sai-niketh-mulakala)  
🔗 [Tableau Profile](https://public.tableau.com/app/profile/sai.niketh.mulakala)

---

