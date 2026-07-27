# 🔬Business Case Studies 

## Overview

This repository contains a collection of business case study projects built using real-world datasets.

Each project approaches the data from a business perspective by simulating real-world analytical scenarios. Every analysis begins with a business objective, explores the data to identify meaningful patterns, develops hypotheses based on observed trends, and concludes with data-driven business insights and recommendations.

The goal of this repository is to demonstrate not only technical proficiency with Python and data analysis libraries, but also the analytical & critical thinking that is involved in solving business problems.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Jupyter Notebook

## 📋 Projects

| Project | Business Goal | Status |
|-||--|
| Retail Revenue Growth Analysis | Investigate inconsistent revenue growth despite increasing sales activity | ✅ Completed |

## 📑 Objectives

Across these projects, I aim to:

- Practice translating business problems into analytical questions
- Strengthen data storytelling skills
- Generate actionable business insights from data
- Build a portfolio demonstrating analytical reasoning alongside technical skills

## Exploratory Analysis Techniques

- Aggregation
- Pivot Tables
- Time-Series Analysis
- Growth Rate Analysis
- Median-based Analysis
- Business KPI Analysis
- Hypothesis-driven Exploration

## 🔨 My Approach

Each project follows a structured analytical workflow inspired by real business investigations.

```text
Business Goal
        │
        ▼
Data Understanding
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Analysis
        │
        ▼
Identify Patterns & Trends
        │
        ▼
Generate Business Hypotheses
        │
        ▼
Hypothesis-Driven Analysis
        │
        ▼
Business Insights
        │
        ▼
Recommendations
```

Instead of randomly exploring variables, every analysis is guided by a business question.

For example:

- Why is revenue growth inconsistent?
- Which customer segments contribute most to profit?
- What factors influence customer churn?
- Which products should receive greater marketing investment?

This approach transforms EDA from descriptive reporting into an investigative process.


## Repository Structure

```
Business-Case-Studies/
│
├── notebooks/
│   ├── superstore
│       ├── 02_hypothesis_1.ipynb
│       ├── 03_hypothesis_2.ipynb
│       ├── 04_hypothesis_3.ipynb
│       ├── 05_hypothesis_4.ipynb
│       ├── 06_hypothesis_5.ipynb
│       ├── 07_hypothesis_6.ipynb
|   
├── README.md
│
└── requirements.txt
```

## Case Study 1 : Retail Sales Exploratory Data Analysis: Investigating Revenue Growth

### Business Goal
Increase business revenue by identifying factors contributing to inconsistent revenue growth and uncovering opportunities for improvement.

Although overall sales performance appeared positive, preliminary analysis revealed that revenue growth was not increasing proportionally with customer activity. This project investigates the underlying drivers behind this trend using a hypothesis-driven analytical approach.



### Business Problem

The business has experienced:

- Increasing customer orders
- Increasing quantities sold
- Increasing number of products sold

However, revenue growth has fluctuated considerably over time instead of showing a consistent upward trend.

The objective of this analysis is to determine:

> **Why is revenue growth inconsistent despite continuous growth in sales activity?**


### Dataset

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



### Project Workflow

#### 1. Business Performance Overview

Initial analysis focused on annual business performance by examining:

- Total Revenue                 : ~$2.3M
- Total Customers               : 793
- Total Orders                  : 5K
- Total Quantity Sold           : 37871
- Total Products Sold           : 1862
- Year-over-Year Revenue Growth : 20% increase in 2017 in comparison to 2016

#### Key Finding

Although revenue increased overall, growth was inconsistent compared to the steady increase observed in customer orders and product sales.



#### 2. Time-Series Exploration

To identify hidden trends, analysis was performed at multiple time granularities.

##### Quarterly Analysis

Examined:

- Quarterly Revenue
- Quarter-over-Quarter Revenue Growth

Finding:

- Revenue experienced recurring declines every 2–3 quarters.



#####  Monthly Analysis

Examined:

- Monthly Revenue
- Monthly Revenue Growth
- Median Monthly Order Value

Finding:

- Several months consistently showed revenue declines across multiple years.
- Median Order Value exhibited a downward trend despite increasing order volumes.



### Hypothesis-Driven Analysis

Based on initial findings, the following business hypotheses were developed.

#### Hypothesis 1

> Declining Median Order Value is contributing to inconsistent revenue growth.

Analysis included:

- Annual Median Order Value
- Quarterly Median Order Value
- Monthly Median Order Value

Outcome:

The analysis supports the hypothesis, indicating that customers are placing lower-value orders over time despite increasing purchase frequency.



#### Hypothesis 2

> Certain product categories contribute more significantly to declining Median Order Value.

Analysis included:

- Revenue growth by Category
- Quantity growth by Category
- Median Order Value by Category
- Revenue share for category

Outcome:

- Technology and to some extent Furniture, are contributing towards the decline in Median Order Value.

#### Hypothesis 3
> There has been an increase in discount provided across products, contributing to lower Median Order Value and inconsistent revenue growth.

Analysis included:
- Overall discount trend
- Discount by Category
- Discout distribution
- Revenue vs Discount

Outcome:
- Discount levels remained relatively stable across years and categories, indicating that the company's pricing strategy did not become more aggressive over time. 
- The decline in Median Order Value and inconsistent revenue growth are more likely explained by other factors, such as changes in product mix, customer purchasing behaviour, or order composition.

### Key Business Insights

- Business growth was driven by increasing customer activity rather than higher-value purchases.
- Median Order Value steadily declined throughout the analysis period.
- Revenue growth was inconsistent despite increasing order counts.
- Revenue declines occurred repeatedly during specific months and quarters.
- Product categories exhibited different revenue and quantity growth patterns, suggesting category-specific purchasing behavior.



### Business Recommendations

Potential strategies to improve revenue include:

- Increase Average/Median Order Value through product bundling.
- Promote higher-value product categories.
- Investigate pricing and discount strategies within Technology and Furniture.
- Develop targeted campaigns during historically weaker months.
- Optimize product mix to increase revenue per customer order.


# 📌 Key Learning

One of the biggest lessons I've taken from these projects is that effective analysis is not only about producing as many visualizations as possible.

It is also about asking meaningful questions, allowing the data to guide the investigation, and communicating findings in a way that supports informed decision-making.

Each project in this repository reflects that philosophy by treating data analysis as an iterative process of observation, hypothesis generation, investigation, and interpretation.


## 📔 Contact

If you'd like to discuss these projects, share feedback, or connect, feel free to reach out through LinkedIn.
