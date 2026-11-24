# Telco Customer Churn Analysis (Excel)

## Problem
A telecom company is losing customers. Which customers leave, and how much revenue does that cost?

## Data
IBM Telco Customer Churn dataset (Kaggle): 7,043 customers, 21 columns
(contract type, tenure, monthly charges, services, churn status).

## What I did
- Cleaned the data: removed duplicate rows, replaced 11 blank TotalCharges
  (new customers with tenure 0) with 0, converted the data to an Excel Table
- Added a Tenure Group column (0-12, 13-24, 25-48, 49+ months)
- Calculated KPIs with COUNTIFS, SUMIFS and AVERAGEIFS
- Built PivotTables and charts, and combined them into a one-page dashboard

## Key findings
- Overall churn rate is 26.5% (1,869 of 7,043 customers)
- Month-to-month contracts churn at 43%, versus 3% for two-year contracts
- First-year customers churn at 47%, falling to 9.5% after 4 years
- Churned customers are 27% of customers but 31% of monthly revenue
- Churned customers pay about 21% more per month (74 vs 61) and stay about
  half as long (18 vs 38 months)

## Recommendations
1. Offer discounts or perks to move month-to-month customers onto 1-2 year contracts
2. Set up a first-year onboarding programme with check-in calls and early offers
3. Prioritise retention offers for new month-to-month customers, the highest-risk group

## Files
- `Telco_Churn_Analysis.xlsx`: data, KPI sheet, pivot and dashboard
- `dashboard.png`: dashboard screenshot

Tools: Excel (COUNTIFS/SUMIFS/AVERAGEIFS, PivotTables, charts)
