# 📊 Credit Card Financial Analysis 

This project demonstrates end-to-end data analysis and visualization using Excel, PostgreSQL, and Power BI, built on real-world datasets sourced from Kaggle. The goal was to analyze customer demographics and transaction behaviors to uncover insights that can drive business decisions in the financial sector.
---

## 🚀 Project Workflow
### ⚪ Data Acquisition
- Downloaded raw CSV datasets from Kaggle (`credit_card_1.csv`, `customer_1.csv`).
### ⚪ Data Cleaning (Excel)
- Cleaned messy and inconsistent data in Excel (handled nulls, standardized formats, removed duplicates, corrected data types).
- Ensured the cleaned datasets were ready for structured database import.
### ⚪ Database Design & SQL Integration
- Created a PostgreSQL database: creditcard_db.
- Designed normalized tables:
- cc_detail → credit card transaction details
- cust_detail → customer demographic details
- Imported cleaned CSV data into PostgreSQL using COPY commands.
- Updated database with additional weekly data (Week 53).
### ⚪ SQL Queries & Data Validation
- Wrote SQL queries to validate imports and ensure data integrity.
- Adjusted session settings (e.g., datestyle) for consistency.
### ⚪ Power BI Dashboards
- Connected PostgreSQL database to Power BI.
- Built **two interactive dashboards:**
      **i) Credit Card Transaction Report →** revenue, transaction counts, expenditure types, card categories, and quarterly trends.
     **ii) Credit Card Customer Report →** customer segmentation by age, gender, income, education, marital status, dependents, and geography.
- Updated dashboards seamlessly when new data was added.

  ---

## 📈 Dashboards Overview
### 🔹 Credit Card Transaction Report
- Revenue & transaction breakdown by card category (Blue, Silver, Gold, Platinum).
- Revenue by expenditure type (Food, Shopping, Travel, Entertainment, Health).
- Quarterly revenue & transaction count trends.
- Insights by customer jobs and education level.
### 🔹 Credit Card Customer Report
- Revenue by age group, gender, income group, marital status, dependents, and education.
- Top 5 states by revenue contribution.
- Customer segmentation by occupation (Businessman, White-collar, Self-employed, etc.).
- Key KPIs: Total Revenue, Total Interest, Customer Satisfaction Score.

---

## 🛠️ Tech Stack
- **Data Cleaning:** Excel
- **Database:** PostgreSQL
- **Visualization:** Power BI
- **Languages/Tools:** SQL, DAX (basic), Excel functions
- **Data Source:** Kaggle

---

## 🎯 Key Learnings & Highlights
- Cleaned and transformed raw Kaggle data in **Excel** before database integration.
- Designed a **scalable data pipeline** from raw CSV → Excel → PostgreSQL → Power BI.
- Applied **SQL for ETL** (Extract, Transform, Load) and validation.
- Built **interactive dashboards** that update dynamically with new data.
- Strengthened skills in **data modeling, visualization, and storytelling.**

  ---
  
## 📌 How This Project Adds Value
- Demonstrates **real-world data analysis workflow** recruiters look for.
- Showcases ability to integrate **Excel, SQL, and BI tools** for business insights.
- Highlights **problem-solving mindset**: handling messy data, updating dashboards with new inputs.
- Relevant for roles in **Data Analysis, Business Intelligence, and Financial Analytics**.

---

## 📷 Dashboards Snapshots
![image alt](https://github.com/Ayan-baksi/Credit_Card_Financial_Dashboards/blob/main/Credit%20Card%20Customer%20Report.png?raw=true)
![image alt](https://github.com/Ayan-baksi/Credit_Card_Financial_Dashboards/blob/main/Credit%20Card%20Transaction%20Report.png?raw=true)

🔮 Next Steps
- Enhance dashboards with predictive insights (e.g., churn risk, revenue forecasting).
- Automate data refresh using scheduled PostgreSQL → Power BI pipelines.
- Explore advanced DAX for deeper KPI calculations.

---

## 👤 Author
Ayan Baksi
- 💼 Aspiring Data Analyst  Excel  SQL  Power BI  Python (Pandas, NumPy, Seaborn)
- 🌐 LinkedIn Profile
- 📧 Contact: ayanbaksi11@gmail.com
---
