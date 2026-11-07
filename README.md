# IKEA Gifting Customer Analytics | RFM Analysis

## Overview

This project explores customer purchasing behavior using transactional retail data. The goal was to understand how customers interact with a retail business, identify high-value customer groups, and uncover patterns that could support better customer retention and marketing decisions.

I used SQL, Python, Excel, and Power BI to clean the data, perform RFM analysis, and build an interactive dashboard.

The project is based on the UCI Online Retail II dataset and uses an IKEA Gifting concept for the analysis. It is an independent learning project and is not affiliated with IKEA.

## Business Questions

The analysis focuses on the following questions:

- Which customers contribute the most to revenue?
- How recently and frequently are customers making purchases?
- Which customer segments are most valuable to the business?
- How many customers show signs of inactivity?
- Are there seasonal patterns in sales?
- How can customer segmentation help improve retention?

## Tools Used

- **SQL Server / SSMS:** Data querying and working with the dataset
- **Python:** Data cleaning and analysis using Pandas
- **Excel:** Data review and preparation
- **Power BI:** Dashboard development and visualization
- **DAX:** Measures and calculations for the dashboard

## Project Workflow

1. Reviewed and prepared the retail transaction dataset.
2. Cleaned the data and handled inconsistencies.
3. Explored customer and sales patterns using Python.
4. Calculated Recency, Frequency, and Monetary values for customer segmentation.
5. Grouped customers based on their RFM scores.
6. Created an interactive Power BI dashboard to present the findings.

## RFM Analysis

RFM stands for:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer purchases.
- **Monetary:** How much a customer spends.

These metrics were used to segment customers into groups such as:

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Cannot Lose Them
- Hibernating

The segmentation helps distinguish customers who are actively contributing to revenue from those who may need additional engagement.

## Key Findings

Some of the key observations from the analysis:

- Champions accounted for approximately 22% of customers and contributed around 68% of revenue.
- Approximately 50.86% of customers were classified as churned based on the project's 90-day inactivity definition.
- Sales showed seasonal patterns, with higher activity during Q4.
- Customer segments varied considerably in purchasing frequency and monetary contribution.

These findings highlight the importance of customer retention and targeted marketing rather than treating all customers the same.

## Power BI Dashboard

The dashboard is organized into three pages:

**Home**
- Project introduction
- Dashboard navigation

**Business Overview**
- Sales and revenue KPIs
- Customer overview
- Sales trends
- Country-level insights

**RFM Analysis**
- Customer segmentation
- RFM distribution
- Segment-level performance
- Customer behavior insights


## Dataset

The project uses the **Online Retail II** dataset from the UCI Machine Learning Repository.

The dataset contains retail transaction records, including invoice details, product information, quantities, prices, customer IDs, and countries.

Dataset: https://archive.ics.uci.edu/dataset/502/online+retail+ii

## What I Learned

Working on this project helped me practice:

- Data cleaning and preprocessing
- Customer segmentation using RFM
- Exploratory data analysis with Pandas
- Understanding retail business metrics
- Building interactive dashboards in Power BI
- Using data to identify potential business opportunities

## Limitations

The customer segments and churn definition are based on the assumptions used in this project. The findings are exploratory and should not be treated as actual IKEA business results.

This project is intended for educational and portfolio purposes.

## Acknowledgment

This project was developed independently as a learning exercise. A walkthrough by Mansi Goel was used as a reference during the learning process.

## Author

**Shanmukhi Shikaram**

AI | Data Science | UI/UX Design
