# Finance Analytics Dashboard

## Overview
An interactive Power BI dashboard (FinSight) that helps management monitor financial transactions, customer behavior, fees, taxes and regional performance in one place. It tracks growth, transaction success, customer segments, states and transaction types, with year-over-year (YoY) comparison.

## Business Problem
The management team needed clear visibility into:
- Overall transaction growth and financial performance
- Monthly trends in transaction amounts
- Successful vs. failed vs. pending transactions
- Customer segment and state-wise contribution
- Transaction type profitability (amount, fees, tax)
- Gender-based customer analysis
- YoY performance changes

## Dataset
- **finance_transactions** – transaction_id, transaction_date, transaction_type, transaction_status, merchant_category, amount, fees, tax
- **customers** – customer_name, gender, customer_segment, state, occupation
- **Calender Table** – date table for year, month and YoY analysis
- **Dynamic Metric** – field parameter to switch measures
- **Scope:** 14.94K transactions in 2025 (₹137.53M)

## Tools & Technologies
- **Power BI** – data modeling and dashboard design
- **DAX** – KPI and YoY measures
- **Word** – business requirements and project report

## Project Steps
1. **Requirements** – Defined 5 KPIs, 6 charts and 4 filters.
2. **Data Modeling** – Connected transactions, customers and a date table.
3. **DAX Measures** – Created Total Amount, Total Transactions, Average Transaction Value, Total Fees, Total Tax and YoY % measures.
4. **Dynamic Metric** – Added a field parameter so users can switch measures.
5. **Dashboard Design** – Built a two-page report with Year, Dynamic Metric, Occupation and Category filters.
6. **Report** – Documented the findings and recommendations.

## Dashboard

### Key Features
- **KPI cards:** Total Amount, Total Transactions, Average Transaction Value, Total Fees, Total Tax (each with YoY change)
- **Visuals:**
  - Total Amount by Month
  - Total Amount by Transaction Status
  - Total Amount by Customer Segment
  - Total Amount by State
  - Transaction Type Analysis (matrix)
  - Total Amount by Gender
- **Transaction page:** Drillthrough table with transaction-level details

## Results (2025)
- **Total amount:** ₹137.53M (+1.41% YoY)
- **Total transactions:** 14.94K (-0.57% YoY)
- **Average transaction value:** ₹9.20K (+1.98% YoY)
- **Total fees:** ₹216.94K (-0.17% YoY)
- **Total tax:** ₹39.04K (-0.22% YoY)
- **Transaction status:** Success 85.4%, Failed 10.4%, Pending 4.2%
- **Top segment:** Retail (₹76M), followed by Premium (₹26M) and SME (₹21M)
- **Top state:** Maharashtra (₹22M), followed by Karnataka (₹16M) and Gujarat (₹15M)
- **Top transaction type:** Loan EMI (₹40.0M amount, ₹64.0K fees)
- **Monthly trend:** Peak in July, lowest in September

## Business Recommendations
- **Expand High-Value Segments** – Retail generates the majority of revenue. Introduce targeted offers for Corporate and Wealth customers.
- **Improve Transaction Success** – Around 14.6% of transaction value is failed or pending. Identify the root causes and monitor the success rate regularly.
- **Strengthen Regional Performance** – Launch focused campaigns in lower-performing states such as Haryana and Kerala.
- **Optimize Fee Strategy** – Review pricing for Loan EMI and Deposit, which contribute the most fees.
- **Address Seasonal Dips** – Plan campaigns for February, September and November.

## Skills Demonstrated
- Data modeling and DAX in Power BI
- KPI design and YoY analysis
- Dashboard design and interactive filtering
- Business insight and recommendation writing
- Documentation of business requirements

## Repository Structure
```
├── finance_dashboard.pbix
├── Business_Requirements.docx
├── Finance_Analytics_Dashboard.docx
└── screenshots/
    ├── page1_overview.png
    └── page2_transactions.png
```

## Author
**Kaustubh Prabhu**

