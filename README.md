
This dashboard analyzing UPI Analysis / Digital payment transcations : success rate, failed vs successful transactions, hourly trends, and monthly volume
# Digital Payment Transaction (UPI) Analysis Dashboard - Power BI

## Overview
This Power BI dashboard provides analysis of Digital Payment and UPI transactions. It tracks success rates, failed vs successful transactions, hourly trends, and monthly volume to monitor payment system performance.

## Features
1. **KPI Cards**: 
   - Success Rate: 50.20%
   - Total Transaction Amount: 5.00M
   - Average Transaction Amount: 5.00K
   - Total Transactions: 1K
   - Successful Transactions: 502
   - Failed Transactions: 498
2. **Transaction Status Distribution**: Donut chart showing 50.2% Success vs 49.8% Failed
3. **Transaction by Hour**: Bar chart showing transaction volume across 24 hours. Peak hours visible around 9-11 AM
4. **Transaction ID by Month**: Bar chart comparing June vs July transaction volume
5. **Filters**: Month, Status, and Day slicers for interactive analysis

## Pages
1. **DIGITAL PAYMENTS**: Current dashboard with KPIs and trends
2. **EXECUTIVE SUMMARY**: High level overview
3. **TRANSACTION ANALYSIS**: Detailed breakdown

## Dataset
Dataset includes UPI/Digital payment data with fields: Transaction ID, Date, Time, Amount, Status, Month, Day

## Tools & Technologies
1. Power BI Desktop (for dashboard design)
2. Power Query (for data cleaning and transformation)
3. DAX (for KPIs: Success Rate, Avg Amount)
4. Excel/CSV (for transaction data source)

## Key Insights
- **Success Rate**: 50.20% of transactions were successful, 49.8% failed
- **Transaction Volume**: 1K total transactions with 5.00M total amount
- **Peak Hours**: Highest transaction activity observed during mid-morning hours
- **Monthly Trend**: June had significantly higher transaction volume than July
- **Avg Ticket Size**: Average transaction amount is 5.00K
