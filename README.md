# 🏥 Healthcare Claims Fraud, Waste, and Abuse (FWA) Analysis - SQL Phase

### 🎯 Project Overview
This project focuses on using SQL and Python to analyze simulated healthcare claims data for a major insurance payer. The core objective is to identify financial risks related to Fraud, Waste, and Abuse (FWA) and perform critical data governance checks.

### 🛠️ Key Technical Skills Demonstrated (SQL)
The analysis effectively uses advanced SQL concepts for financial auditing and compliance:
* **Window Functions:** DENSE_RANK() and SUM() OVER for ranking and calculating running totals.
* **Complex Aggregation:** GROUP BY and HAVING clauses to identify high-frequency abusers.
* **Date Functions:** DATEDIFF() for compliance checks (Claims Lag).
* **Conditional Logic:** CASE statements for overbilling fraud detection.

### 📊 Key Analysis Objectives
The analysis addresses the following business critical questions:
1.  **Overbilling Audit:** Flagging claims billed 150% above the national average cost.
2.  **Specialty Benchmarking:** Identifying the Top 2 highest-billing providers within each medical specialty.
3.  **Abuse Pattern Detection:** Identifying providers who submit high-risk procedures frequently.
4.  **Financial Trend Analysis:** Calculating the cumulative billed amount for specific providers.
5.  **Compliance Check:** Identifying non-compliant claims submitted after a 90-day service-date deadline.
