# Retail Sales Exploratory Data Analysis: Investigating Revenue Growth

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on historical retail sales data to simulate a real-world business scenario.


## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly *(if applicable)*
- Jupyter Notebook

---

## Exploratory Analysis Techniques

- Aggregation
- Pivot Tables
- Time-Series Analysis
- Growth Rate Analysis
- Median-based Analysis
- Business KPI Analysis
- Hypothesis-driven Exploration

---


## Repository Structure

```
Retail-Revenue-EDA/
│
├── data/
│   ├── retail_sales.csv
│
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_Exploratory_Analysis.ipynb
│   ├── 03_Hypothesis_Analysis.ipynb
│
├── visuals/
│   ├── yearly_trends.png
│   ├── quarterly_trends.png
│   ├── monthly_trends.png
│   ├── category_analysis.png
│
├── README.md
│
└── requirements.txt
``


### Business Goal
Increase business revenue by identifying factors contributing to inconsistent revenue growth and uncovering opportunities for improvement.

Although overall sales performance appeared positive, preliminary analysis revealed that revenue growth was not increasing proportionally with customer activity. This project investigates the underlying drivers behind this trend using a hypothesis-driven analytical approach.

---

## Business Problem

The business has experienced:

- Increasing customer orders
- Increasing quantities sold
- Increasing number of products sold

However, revenue growth has fluctuated considerably over time instead of showing a consistent upward trend.

The objective of this analysis is to determine:

> **Why is revenue growth inconsistent despite continuous growth in sales activity?**

---

## Dataset

The dataset contains historical retail transaction data including:

- Order Date
- Order ID
- Product
- Category
- Sub-Category
- Customer Segment
- Region
- Sales (Revenue)
- Quantity
- Discount *(if available)*

Data spans four years:

- 2014
- 2015
- 2016
- 2017

---

## Project Workflow

### 1. Business Performance Overview

Initial analysis focused on annual business performance by examining:

- Total Revenue                 : ~$2.3M
- Total Customers               : 793
- Total Orders                  : 5K
- Total Quantity Sold           : 37871
- Total Products Sold           : 1862
- Year-over-Year Revenue Growth : 20% increase in 2017 in comparison to 2016

### Key Finding

Although revenue increased overall, growth was inconsistent compared to the steady increase observed in customer orders and product sales.

---

### 2. Time-Series Exploration

To identify hidden trends, analysis was performed at multiple time granularities.

#### Quarterly Analysis

Examined:

- Quarterly Revenue
- Quarter-over-Quarter Revenue Growth

Finding:

- Revenue experienced recurring declines every 2–3 quarters.

---

#### Monthly Analysis

Examined:

- Monthly Revenue
- Monthly Revenue Growth
- Median Monthly Order Value

Finding:

- Several months consistently showed revenue declines across multiple years.
- Median Order Value exhibited a downward trend despite increasing order volumes.

---

## Hypothesis-Driven Analysis

Based on initial findings, the following business hypotheses were developed.

### Hypothesis 1

> Declining Median Order Value is contributing to inconsistent revenue growth.

Analysis included:

- Annual Median Order Value
- Quarterly Median Order Value
- Monthly Median Order Value

Outcome:

The analysis supports the hypothesis, indicating that customers are placing lower-value orders over time despite increasing purchase frequency.

---

### Hypothesis 2

> Certain product categories contribute more significantly to declining Median Order Value.

Analysis included:

- Revenue growth by Category
- Quantity growth by Category
- Median Order Value by Category
- Revenue trends for Sub-Categories

Outcome:

- Technology and to some extent Furniture, are contributing towards the decline in Median Order Value.


---

## Key Business Insights

- Business growth was driven by increasing customer activity rather than higher-value purchases.
- Median Order Value steadily declined throughout the analysis period.
- Revenue growth was inconsistent despite increasing order counts.
- Revenue declines occurred repeatedly during specific months and quarters.
- Product categories exhibited different revenue and quantity growth patterns, suggesting category-specific purchasing behavior.

---

## Business Recommendations

Potential strategies to improve revenue include:

- Increase Average/Median Order Value through product bundling.
- Promote higher-value product categories.
- Investigate pricing and discount strategies within Technology and Furniture.
- Develop targeted campaigns during historically weaker months.
- Optimize product mix to increase revenue per customer order.

---
`

---

## Future Work

Further investigation could include:

- Customer segmentation analysis
- Regional performance analysis
- Discount impact analysis
- Product-level profitability
- Predictive revenue forecasting
- Customer lifetime value analysis

---

## Conclusion

This project demonstrates how Exploratory Data Analysis can be used to investigate business performance beyond descriptive reporting. By following a hypothesis-driven approach, the analysis identifies potential drivers behind inconsistent revenue growth and provides actionable insights that can support data-informed business decisions.
