# IKEA Gifting – Customer Analytics & RFM Segmentation

## Project Overview

This project focuses on analyzing customer purchasing behavior for IKEA Gifting, a UK-based online retailer specializing in giftware and home decor.

The objective is to identify valuable customer segments, understand purchasing patterns, measure customer retention, and identify customers at risk of churn using historical transaction data.

The project follows an end-to-end data analytics approach using Excel, SQL, Python, and Power BI.

## Business Objectives

- Identify the most valuable customers based on their purchasing behavior.
- Perform customer segmentation using RFM (Recency, Frequency, Monetary) analysis.
- Identify customers at risk of churn using a 90-day inactivity threshold.
- Analyze customer revenue contribution and purchasing trends.
- Compare customer value and retention across different countries.
- Provide actionable business recommendations for different customer segments.

## Dataset

**Dataset:** Online Retail II

**Source:** UCI Machine Learning Repository

**Time Period:** December 2009 – December 2011

**Original Dataset Size:** 1,067,371 transaction records.

The dataset contains invoice details, product descriptions, quantities, unit prices, customer IDs, and country information.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Initial data exploration and analysis |
| SQL | Data extraction, cleaning, and querying |
| Python | Data processing and RFM segmentation |
| Power BI | Interactive dashboard and business insights |

## Project Workflow

### 1. Excel – Data Exploration
- Initial dataset inspection.
- Understanding transaction-level data.
- Exploring customer purchasing patterns.

### 2. SQL – Data Cleaning & Analysis
- Data extraction and cleaning.
- Handling invalid transaction records.
- Preparing analysis-ready data.
- Customer-level transaction analysis.

### 3. Python – RFM Analysis
- Calculating Recency, Frequency, and Monetary values.
- Assigning customer RFM scores.
- Segmenting customers into business categories.
- Identifying churn risk using a fixed 90-day inactivity threshold.

### 4. Power BI – Dashboard Development
Developed a three-page interactive dashboard:

- Home / Navigation Page
- Business Overview
- RFM Analysis

The dashboard supports customer segmentation, revenue analysis, country-level comparisons, and business performance insights.

## Customer Segments

The analysis categorizes customers into the following segments:

- **Champions:** Most valuable customers.
- **Loyal:** Customers with consistent purchasing behavior.
- **At Risk:** Previously valuable customers showing declining engagement.
- **New:** Recently acquired customers.
- **Needs Attention:** Customers with low purchasing frequency.
- **Lost:** Customers with extended inactivity.

## Key Business Deliverables

- Cleaned and analysis-ready transaction dataset.
- Customer-level RFM scores and segment assignments.
- Churn-flagged customer list.
- Interactive Power BI dashboard.
- Business insights and recommended actions for each customer segment.

## Project Scope & Limitations

- Churn is identified using a fixed 90-day inactivity threshold.
- The analysis uses historical transaction data.
- Predictive machine learning-based churn modeling is outside the project scope.
- Individual product-level recommendations and automated marketing campaigns are not included.


## Conclusion

This project demonstrates how data analytics tools can transform raw transaction data into meaningful customer insights, helping businesses understand customer value, identify potential churn, and develop more targeted retention strategies.
