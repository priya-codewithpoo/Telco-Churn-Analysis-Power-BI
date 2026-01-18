# 📊 Power BI Customer Churn Analysis (Telco Dataset)

![Dashboard Overview](./images/Dashboard.png)

---

## 💡 Project Summary

This Power BI project analyzes Telco customer churn to identify high-risk segments and retention opportunities. Interactive dashboards highlight critical metrics, enabling data-driven business decisions.

---

## 🔍 Project Overview
This project analyzes customer churn for a telecom company to identify **why customers leave, which segments are at highest risk, and where retention strategies should focus**. 

The final deliverable is an executive-style interactive dashboard designed for decision-makers. This project demonstrates hands-on business analytics using Power BI to analyze telecom customer churn.

---

## 🎯 Business Objectives
* **Identify High-Risk Segments:** Pinpoint specific demographics and service tiers impacting revenue.
* **Analyze Operational Drivers:** Determine if service types (like Fiber Optic) or contract lengths drive churn.
* **Highlight Retention Opportunities:** Identify the "Safe Zone" and "Danger Zone" to guide marketing spend.

---
## 📂 Project Structure
* [telco_churn_analysis.pbix](./telco_customer_churn.pbix): The main Power BI file.
* [data](./telco_customer_churn_data.csv): Raw and cleaned CSV datasets.
* [images](./images/): High-resolution screenshots used for documentation.
---

## 📊 Dashboard Preview

### 1. Executive Churn Overview
High-level KPIs (Total Customers, Churn Rate, Avg Revenue) 

### 2. Diagnostic Risk Heatmap (The "Deep-Dive")
Identifies “Danger Zone” customers with highest churn risk (e.g., Fiber Optic, Month-to-Month).
![Churn Heatmap](./images/highest_churn_risk_matrix.png)

### 3. Tenure Trend Analysis (The "Lifecycle") 
Highlights high churn in first 12 months to inform retention strategies
![Tenure Trend Analysis](./images/customer_tenure.png)

---

## 🧠 Key Business Questions Answered
* **Revenue leak:** High-monthly-charge Fiber Optic customers

* **Safe Zone:** Two-Year DSL contracts with low churn (<3%)

* **Target:** New Month-to-Month customers (Tenure <6 months) for retention

---

## 🛠️ Tools & Technologies
* **Power BI Desktop:** End-to-end dashboard design and UI/UX implementation.
* **Power Query:** Data transformation (handling missing values in "Total Charges" and data type standardization).
* **DAX (Data Analysis Expressions):**
    * `Total Customers = COUNT(TelcoData[CustomerID])`
    * `Churn Rate % = DIVIDE([Churn Count], [Total Customers])`
    * `Avg Revenue = AVERAGE(TelcoData[MonthlyCharges])`

---

## 📈 Key Learnings
* Focused on actionable insights and storytelling

* Applied dashboard UI/UX best practices (alignment, colors, white space)

* Solved tool limitations creatively for professional visuals

---

## 🏁 Conclusion

This project demonstrates how raw data can be transformed into actionable business intelligence, enabling targeted retention strategies to protect high-value revenue.



