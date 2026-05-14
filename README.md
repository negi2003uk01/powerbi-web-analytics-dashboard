# Web Traffic Analytics Dashboard

## Project Overview

This project is a Web Traffic Analytics Dashboard built using Microsoft Power BI.
The dashboard analyzes website performance, user engagement, traffic sources, sessions, revenue trends, and conversion metrics using interactive visualizations and DAX measures.

The goal of this project is to transform raw web analytics data into meaningful business insights through data cleaning, modeling, and visualization.

---

## Tools & Technologies Used

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel

---

## Dataset Information

The dataset contains website analytics data including:

* Users
* New Users
* Sessions
* Revenue
* Transactions
* Bounce Rate
* Conversion Rate
* Avg Session Duration
* Source / Medium
* Monthly website activity

---

## Data Cleaning & Transformation

Performed multiple data cleaning and transformation steps including:

* Cleaned Bounce Rate and Conversion Rate columns
* Converted percentage values into proper numeric format
* Handled inconsistent values such as `<0.01`
* Converted session duration into valid time format
* Built relationships between tables for proper filtering

---

## DAX Measures Created

Some important DAX measures used in the dashboard:

```DAX
Total Users = SUM('Web Analytic_Dataset'[Users])

New Users = SUM('Web Analytic_Dataset'[New Users])

Total Revenue = SUM('Web Analytic_Dataset'[Revenue])

Total Sessions = SUM('Web Analytic_Dataset'[Sessions])

Avg Bounce Rate =
AVERAGE('Web Analytic_Dataset'[Bounce Rate Clean])

Avg Conversion Rate =
AVERAGE('Web Analytic_Dataset'[Conversion Rate Clean])
```

---

## Dashboard Features

### Page 1 – Executive Overview

* Total Users KPI
* New Users KPI
* Total Units Sold KPI
* Revenue Trend by Month
* User Growth Trend
* Sessions Trend
* Pageviews Trend
* Bounce Rate Trend
* Avg Session Duration by Source
* Interactive slicers:

  * Year
  * Month
  * Source / Medium

### Page 2 – Source Performance Analysis

* Revenue by Source
* Sessions by Source
* Conversion Rate by Source
* Top Performing Channels Table
* Source-wise performance comparison

---

## Key Business Insights

* Identified top-performing traffic sources
* Analyzed monthly revenue growth trends
* Compared user engagement across channels
* Evaluated bounce rate and conversion performance
* Tracked website traffic and session behavior over time

---


## Project Outcome

This project helped strengthen skills in:

* Power BI Dashboard Development
* DAX Calculations
* Data Cleaning
* Data Modeling
* Business Intelligence Reporting

---
