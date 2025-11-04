# Banking-Analytics-Dashboard
A Power BI–based banking analytics solution analyzing customer demographics, income distribution, loans, and deposits to identify high-value client segments and financial behavior patterns. Includes data cleaning in Python, KPI modeling using DAX, and interactive dashboards with insights for strategic banking decisions.
# 🏦 Banking Analytics Dashboard | Power BI Project

### 📌 Overview
This project analyzes banking customer data to uncover insights related to customer demographics, financial product usage, income patterns, and loan-deposit distributions.  
The goal is to help banking stakeholders identify high-value customer segments, optimize product offerings, and support data-driven financial decision-making.

---

## 🎯 Project Objectives
- Analyze customer financial behavior and product holding patterns
- Evaluate loan and deposit distribution across demographic segments
- Identify high-value customer profiles based on income and assets
- Build interactive visual dashboards for business users
- Create DAX-based KPIs for financial performance monitoring

---

## 📊 Key KPIs & Metrics
- Total Loan Value  
- Total Deposit Value  
- Customer Count  
- Average Customer Income  
- Average Properties Owned  
- Credit Card & Business Lending totals  

---

## 🧠 Key Insights
| Category | Insight |
|---|---|
High-Value Customers | High-income customers & business owners contribute ~52% of total deposits  
Loan Distribution | Males ~55% loan share; business & professional segments lead  
Deposit Drivers | Savings + Checking = ~70% of deposits, strongest among higher income brackets  
Wealth Indicators | Customers owning 2+ properties hold ~38% higher combined balances  
Customer Relationship Trend | Private & Commercial banking customers contribute majority of value  

---

## 🛠️ Tech Stack
| Component | Tools |
|---|---|
Data Cleaning & Prep | Python (Pandas)  
Data Visualization | Power BI  
Modeling & KPIs | DAX Calculated Measures  
Data Format | CSV  

---

## 📂 Project Structure

📁 Banking-Analytics-Dashboard

├── Banking.csv

├── banking_dashboard.pbix

├── BANKING_ANALYSIS.ipynb

├── screenshot

├── presentation

└── README.md
---

---

## 📐 DAX Measures Used

```DAX
Total Loan =
SUM('Banking'[Bank Loans]) +
SUM('Banking'[Business Lending]) +
SUM('Banking'[Credit Card Balance])

Total Deposit =
SUM('Banking'[Bank Deposits]) +
SUM('Banking'[Saving Accounts]) +
SUM('Banking'[Checking Accounts]) +
SUM('Banking'[Foreign Currency Account])

Avg Income = AVERAGE('Banking'[Income])
Total Customers = DISTINCTCOUNT('Banking'[CustomerID])

----

📸 Dashboard Preview

![overview](https://github.com/user-attachments/assets/527eb778-93a5-462f-87bf-59cf923c5fec)

✅ Overview Dashboard


![Loan Analysis](https://github.com/user-attachments/assets/dcd12891-f385-418d-83bf-4d45ccdb8ce7)

✅ Loan Analysis Dashboard


![Deposit Analysis](https://github.com/user-attachments/assets/456e6d43-cc5a-432c-afdc-7845460a47b3)

✅ Deposit Analysis Dashboard


![Summary](https://github.com/user-attachments/assets/7bcb49ca-f02b-4fec-ace9-ec1d5610ba95)

✅ Customer Summary Dashboard

👤 Author

Shreya Kumari
BI & Data Analyst | Power BI | SQL | Python
🌐 LinkedIn: linkedin.com/in/shreya-k-986a8321b 
