# DS310 Project: COVID-19 Policy Analysis

## 📋 Project Overview
This project was conducted as part of the DS310 course to identify the most effective, yet least restrictive policies that the government of Caladan can implement to maintain COVID-19 growth rates below critical thresholds:
- **Deaths Growth Rate:** Below 1% (30-day rolling average)
- **New Cases Growth Rate:** Below 3% (30-day rolling average)

The project was divided into four key phases:
1. **Data Extraction and Loading**
2. **Data Transformation**
3. **Processed Data Loading**
4. **Data Analysis and Visualization**

---

## 📊 Data Sources
- **Policy Data:** Cosmos DB (SQL API)
- **COVID-19 Cases, Recoveries, Deaths:** Azure SQL DB & On-Premises Virtual Machines
- **Data Storage:** Organized in Parquet format within a Data Lake

---

## ⚙️ Technologies Used
- **Data Processing:** Azure Synapse, Data Lake, GitHub
- **Visualization:** Power BI
- **Analytics:** Python, SQL
- **Data Modeling:** Snowflake Schema

---

## 🚀 Analysis & Key Findings
- **Policy Success Metrics:** Evaluated based on rolling average success rates
- **Power BI Dashboards:** Created decomposition trees to identify impactful policy combinations
- **Policy Combinations:** 52 combinations had a 100% success rate, with 4 active for over 20 days

---

## 📈 Project Insights
- Policies with **lower stringency indices** and high success rates were prioritized
- South Korea's policy set balanced effectiveness with minimal restrictions
- Data-driven approach validated through Power BI visualizations
