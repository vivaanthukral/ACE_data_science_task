# ACE Coding Club - Task Solutions & Problem Sets

Welcome to the official repository for **ACE Coding Club** assignments, projects, and solutions. This repository contains structured solutions and analyses across Data Analytics, SQL Database Management, and Data Science.

---

## 📌 Tasks & Modules Overview

### 1. Social Media Performance Analytics
* **Domain:** Data Analytics / Excel & Data Visualization
* **Objective:** Evaluate social media engagement metrics and audience interaction across various content types and platforms.
* **Key Components:**
  * Identified top-performing content types based on share volume.
  * Engineered an **Engagement Rate** metric:
    $$\text{Engagement Rate} = \frac{\text{Likes} + \text{Comments} + \text{Shares}}{\text{Total Impressions}}$$
  * Created Pivot Tables and comparative bar charts analyzing impressions vs. likes across platforms.

---

### 2. Retail Sales Analytics with SQL
* **Domain:** Database Management & SQL
* **Objective:** Analyze retail transactional data to extract customer spending insights and product sales trends.
* **Key Components:**
  * Calculated baseline metrics: total revenue, average transaction value, and total volume sold.
  * Categorical sales analysis to pinpoint the highest-grossing product categories.
  * Applied `JOIN` operations and aggregation functions to identify top 5 high-value customers and total order distributions.

---

### 3. Exploratory Data Analysis (EDA) on House Prices
* **Domain:** Data Science & Python
* **Objective:** Uncover key drivers of housing prices through statistical profiling and multivariate analysis.
* **Key Components:**
  * Cleaned raw dataset and handled missing/anomalous variables using Python (`pandas`, `numpy`).
  * Plotted feature correlation heatmaps and regression trendlines (`seaborn`, `matplotlib`).
  * Extracted actionable real-estate pricing factors based on statistical significance.

---

## 📂 Repository Structure

```text
├── Social-Media-Analytics/
│   ├── dataset/
│   ├── social_media_analysis.xlsx
│   └── README.md
├── Retail-Sales-SQL/
│   ├── queries/
│   │   ├── total_metrics.sql
│   │   ├── category_sales.sql
│   │   └── top_customers.sql
│   └── README.md
├── House-Price-EDA-Python/
│   ├── notebooks/
│   │   └── eda_house_prices.ipynb
│   ├── data/
│   └── README.md
└── README.md