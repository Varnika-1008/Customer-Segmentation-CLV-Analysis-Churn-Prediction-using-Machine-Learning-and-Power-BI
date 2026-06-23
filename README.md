# Customer Segmentation, CLV Analysis & Churn Prediction

## Overview

This project presents an end-to-end customer analytics solution built using the Olist E-commerce dataset. The objective is to analyze customer behavior, identify valuable customer segments, estimate customer lifetime value (CLV), predict customer churn, and visualize business insights through an interactive Power BI dashboard.
The project combines data preprocessing, feature engineering, machine learning, customer analytics, and business intelligence to support data-driven decision making.

---

## Business Problem

E-commerce businesses need to answer critical questions such as:

- Which customers generate the highest revenue?
- Which customers are likely to churn?
- What is the estimated lifetime value of each customer?
- How do customer segments differ in behavior?
- Which regions contribute the most revenue?
- How can businesses improve retention and profitability?

This project addresses these questions using analytical and machine learning techniques.

---

## Dataset

**Dataset:** Olist Brazilian E-Commerce Dataset

The dataset contains:

- Customer information
- Order details
- Payment information
- Product information
- Review scores
- Delivery details

After preprocessing and feature engineering, customer-level insights were generated for segmentation and churn analysis.

---

## Project Workflow

### 1. Data Preprocessing

- Merged multiple Olist datasets
- Removed duplicates and handled missing values
- Filtered relevant transactions
- Created customer-level aggregated features
- Generated time-based and behavioral features

### 2. Customer Segmentation (RFM Analysis)

Customers were segmented using:

- **Recency** – How recently a customer purchased
- **Frequency** – How often a customer purchases
- **Monetary Value** – How much a customer spends

Segments include:

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk Customers
- Lost Customers

### 3. Customer Lifetime Value (CLV)

Calculated customer value using:

- Purchase frequency
- Average order value
- Revenue contribution

CLV tiers were created to identify high-value customers and support retention strategies.

### 4. Churn Prediction

A machine learning pipeline was developed using customer behavioral features such as:

- Recency
- Frequency
- Total Revenue
- Average Order Value
- Review Scores
- Delivery Performance

The model predicts whether a customer is likely to churn.

### 5. Business Intelligence Dashboard

An interactive Power BI dashboard was developed to monitor:

- Revenue performance
- Customer behavior
- Customer segmentation
- Delivery metrics
- Review scores
- Geographic performance
- Segment-wise revenue contribution

---

## Machine Learning Performance

| Metric | Score |
|----------|--------|
| Accuracy | ~80% |
| ROC-AUC | ~0.72 |
| Model Type | Ensemble Learning |

---

## Dashboard Features

### Executive KPIs

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Average Review Score
- Average Delivery Days

### Revenue Analytics

- Revenue Trend Over Time
- Revenue by State
- Revenue by Quarter

### Customer Analytics

- Orders by Review Score
- Weekend vs Weekday Orders
- Customer Segment Distribution

### Logistics Analytics

- Delivery Days Distribution
- Average Delivery Days by State

### Segmentation Insights

- Revenue by Customer Segment
- Orders by Customer Segment
- Average Review Score by Segment

---

## Technologies Used

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Machine Learning

- Scikit-Learn
- XGBoost
- Ensemble Models

### Data Visualization

- Matplotlib
- Seaborn
- Power BI

### Development Environment

- Jupyter Notebook
---

## Project Structure

```text
Customer-Segmentation-CLV-Churn-Prediction/
│
├── notebooks/
│   ├── customer_segmentation.ipynb
│   └── customer_segmentation_improved.ipynb
│
├── data/
│   └── olist_clean_master.csv
│
├── dashboard/
│   ├── Customer_Segmentation_Dashboard.pbix
│   └── dashboard_screenshot.png
│
├── README.md
└── requirements.txt
```

---

```

'''
## Key Outcomes

- Identified high-value customer groups using RFM segmentation
- Built a churn prediction model for customer retention analysis
- Estimated customer lifetime value for strategic decision-making
- Developed an interactive Power BI dashboard for business stakeholders
- Generated actionable insights from 100K+ e-commerce transactions
'''

