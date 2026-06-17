# Customer Shopping Behavior Analysis

## Overview

Customer Shopping Behavior Analysis is an end-to-end Data Analytics project that explores purchasing patterns, customer demographics, product preferences, and subscription behavior using transactional shopping data.

The project follows a complete analytics workflow, including data cleaning and exploratory analysis in Python, business analysis using PostgreSQL, interactive dashboard development in Power BI, report generation, and presentation creation using Gamma.

The objective is to transform raw customer transaction data into actionable business insights that support data-driven decision-making.

---

## Dataset

The dataset contains customer shopping transactions across multiple product categories.

### Dataset Information

* Total Records: 3,900
* Total Features: 18
* Data Type: Structured transactional data

### Key Features

* Customer Demographics

  * Age
  * Gender
  * Location
  * Subscription Status

* Purchase Information

  * Item Purchased
  * Category
  * Purchase Amount
  * Season
  * Size
  * Color

* Shopping Behavior

  * Discount Applied
  * Previous Purchases
  * Frequency of Purchases
  * Review Rating
  * Shipping Type

---

## Tools & Technologies

| Tool                 | Purpose                            |
| -------------------- | ---------------------------------- |
| Python               | Data Processing & Analysis         |
| Pandas               | Data Cleaning & Transformation     |
| NumPy                | Numerical Operations               |
| Matplotlib & Seaborn | Data Visualization                 |
| PostgreSQL           | Database Management & SQL Analysis |
| SQL                  | Business Query Analysis            |
| Power BI             | Dashboard Development              |
| Gamma                | Presentation Creation              |
| Jupyter Notebook     | Analysis Environment               |

---

## Project Steps

### 1. Data Loading

* Imported the dataset using Python and Pandas.
* Examined data structure, data types, and summary statistics.
* Performed initial quality assessment.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics and purchasing patterns.
* Explored category-wise sales performance.
* Studied subscription and discount behavior.
* Visualized trends and distributions using charts and graphs.

### 3. Data Cleaning & Preparation

* Identified and handled missing values.
* Imputed missing review ratings using category-wise median values.
* Standardized column names using snake_case format.
* Removed redundant columns.
* Verified data consistency and quality.

### 4. Feature Engineering

Created additional features to improve analysis:

* Age Group Classification
* Purchase Frequency Metrics
* Customer Segmentation Features

### 5. PostgreSQL & SQL Analysis

Loaded the cleaned dataset into PostgreSQL and executed SQL queries to answer business questions such as:

* Revenue contribution by gender
* Subscriber vs non-subscriber spending behavior
* High-spending discount users
* Top-rated products
* Shipping type comparison
* Discount-dependent products
* Customer segmentation analysis
* Revenue contribution by age group
* Repeat buyer subscription analysis

### 6. Power BI Dashboard Development

* Connected processed data to Power BI.
* Built interactive visualizations and KPI cards.
* Designed filters and drill-down analysis.
* Presented key business insights through an intuitive dashboard.

### 7. Reporting & Presentation

* Prepared a detailed analytical report documenting methodology and findings.
* Created a professional business presentation using Gamma.
* Summarized insights and recommendations for stakeholders.

---

## Dashboard

The Power BI dashboard provides:

* Sales Overview KPIs
* Revenue Analysis
* Customer Segmentation Insights
* Product Performance Metrics
* Subscription Analysis
* Age Group Analysis
* Discount Impact Analysis
* Interactive Filters and Visualizations

The dashboard enables stakeholders to quickly identify trends, customer behavior patterns, and business opportunities.

---

## Results

### Key Findings

* Customer purchasing behavior varies across demographics and subscription status.
* Subscribers contribute significantly to overall revenue.
* Certain products perform exceptionally well in ratings and purchase frequency.
* Discount strategies influence customer spending behavior.
* Loyal customers generate higher long-term business value.
* Age-group analysis reveals high-revenue customer segments.

### Business Recommendations

* Promote subscription programs through exclusive benefits.
* Implement customer loyalty initiatives for repeat buyers.
* Optimize discount strategies to balance sales and profitability.
* Prioritize marketing efforts toward high-value customer segments.
* Highlight top-rated products in promotional campaigns.

---

## How to Run

### Prerequisites

* Python 3.x
* PostgreSQL
* Power BI Desktop
* Jupyter Notebook

### Installation

Clone the repository:

```bash
git clone https://github.com/tejasreeshaga28/customer_behavior_analysis
```

Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn psycopg2
```

### Execution Steps

1. Open the Jupyter Notebook.
2. Load the dataset into Python.
3. Perform data cleaning and EDA.
4. Export the cleaned dataset to PostgreSQL.
5. Run SQL queries for business analysis.
6. Open the Power BI dashboard (.pbix file).
7. Review the report and Gamma presentation for findings and recommendations.

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── shopping_data.csv
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── feature_engineering.ipynb
│
├── SQL/
│   └── business_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
├── Report/
│   └── Customer_Shopping_Behavior_Analysis_Report.pdf
│
├── Presentation/
│   └── Gamma_Presentation.pdf
│
└── README.md
```

---


