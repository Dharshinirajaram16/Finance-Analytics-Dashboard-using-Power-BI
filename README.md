# Finance Analytics Dashboard using Power BI

An end-to-end Power BI project focused on analyzing banking transactions, customer behavior, and financial performance through interactive dashboards, DAX calculations, and drill-through analytics.

---

## 📌 Project Navigation

* [Project Overview](#project-overview)
* [Business Problem](#business-problem)
* [Tools & Technologies](#tools--technologies)
* [Data Quality Assessment](#data-quality-assessment)
* [Data Cleaning Process](#data-cleaning-process)
* [Dashboard Features](#dashboard-features)
* [Dashboard Overview](#dashboard-overview)
* [Specific Month Analysis](#specific-month-analysis)
* [Drill Through Analysis](#drill-through-analysis)
* [DAX Measures](DAX/DAX_Measures.md)
* [Business Insights](#business-insights)
* [Key Learnings](#key-learnings)
* [Future Enhancements](#Future-Enhancements)


---

## Project Overview

The Finance Analytics Dashboard is an end-to-end Power BI project developed to analyze banking transactions and customer behavior. The dashboard enables users to monitor transaction trends, customer segments, revenue metrics, and operational performance through interactive visualizations.

This project covers the complete analytics lifecycle, including data quality assessment, data cleaning, data modeling, DAX calculations, dashboard development, and business insight generation.

---

## Business Problem

Banks process thousands of transactions every day, making it difficult to manually monitor transaction performance and customer activity.

This dashboard was designed to:

* Monitor transaction volume and value
* Analyze customer segments
* Track fee and tax collections
* Compare Year-over-Year performance
* Identify regional transaction trends
* Investigate detailed transaction records through drill-through analysis

---

## Tools & Technologies

* Power BI
* Power Query
* DAX
* Data Modeling
* Data Visualization
* CSV Data Sources

---

## Data Quality Assessment

Before creating the dashboard, data quality checks were performed to ensure accuracy and consistency.

### Validation Performed

✅ Data Type Validation

✅ Duplicate Record Verification

✅ Null Value Verification

✅ Text Standardization

✅ Currency Standardization

✅ Data Profiling

### Data Quality Check

![Data Quality Check](Assets/01_Data_Quality_Check.png)

This step helped identify inconsistencies and ensured that the dataset was suitable for further analysis.

---

## Data Cleaning Process

![Data Cleaning](Assets/2.%20Data%20Cleaning.png)

The dataset was cleaned and transformed using Power Query by:

* Removing duplicate records
* Standardizing text values
* Trimming unwanted spaces
* Correcting data types
* Standardizing currency formats

These transformations improved data quality and reporting accuracy.

---

## Dashboard Features

### KPI Metrics

* Total Amount
* Total Transactions
* Average Transaction Value
* Total Fees
* Total Tax

### Interactive Filters

* Year Filter
* Dynamic Metric Selection
* Occupation Filter
* Category Filter

### Analytics

* Monthly Transaction Analysis
* Transaction Status Analysis
* Customer Segment Analysis
* State-wise Analysis
* Gender Analysis
* Transaction Type Analysis

### 📑 View Complete DAX Measures

➡️ [Open DAX Measures](DAX/DAX_Measures.md)

---

## Dashboard Overview

![Dashboard Overview](Assets/3.%20Dashboard%20Overview.png)

The overview dashboard provides a high-level summary of transaction performance, customer segments, and financial metrics through KPI cards and interactive visualizations.

---
## Project Files

### Power BI Dashboard

Download the Power BI dashboard file:

[Finance Analytics.pbix](Dashboard/Finance%20Analytics.pbix)

## Specific Month Analysis

![Specific Month Analysis](Assets/4.%20Specific%20Month%20Analysis.png)

Users can filter the dashboard for a specific month to analyze transaction trends, customer activity, and revenue metrics for that period.

---

## Drill Through Analysis

![Drill Through Analysis](Assets/5.%20Drill%20Through%20Analysis.png)

The drill-through functionality enables users to navigate from summary-level insights to detailed transaction records.

Example workflow:

1. Select a month from the dashboard.
2. Right-click and choose Drill Through.
3. View only the transactions related to the selected period.

This feature improves transaction investigation and reporting efficiency.

---

## Business Insights

### Customer Insights

* Retail customers contribute the highest transaction volume.
* Premium customers demonstrate strong transaction activity.

### Revenue Insights

* Fee and tax collections contribute to overall revenue generation.
* Year-over-Year analysis helps evaluate business growth trends.

### Transaction Insights

* Successful transactions account for the majority of overall transactions.
* Pending and failed transactions can be monitored to improve operational efficiency.

---

## Key Learnings

Through this project, I strengthened my skills in:

* Data Cleaning using Power Query
* Data Quality Assessment
* Data Modeling
* DAX Calculations
* Time Intelligence Functions
* Dashboard Design
* Business Analytics
* Data Storytelling

---
## Future Enhancements

This project can be extended further by incorporating advanced analytics and AI-powered capabilities:

* Integration with real-time transaction data sources for live dashboard monitoring.
* Development of machine learning models for fraud detection and anomaly identification.
* Implementation of predictive analytics to forecast transaction volume and revenue trends.
* Automated report generation using AI-powered assistants, enabling users to generate business reports and insights through natural language prompts.
* Integration with AI coding and analytics tools to automate data processing, analysis, and dashboard enhancements.
  
