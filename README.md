# 🛒 B2 Mini Mart Sales Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-EDA-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

### 📊 End-to-End Retail Sales Analytics Project

*An end-to-end data analytics project combining Python Exploratory Data Analysis (EDA) and an interactive Power BI dashboard to uncover actionable insights into sales performance, customer behavior, product profitability, and regional business trends.*

</div>

---

# 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Information](#-dataset-information)
- [Tools & Technologies](#-tools--technologies)
- [Project Workflow](#-project-workflow)
- [Repository Structure](#-repository-structure)
- [Installation](#-installation)
- [Dashboard Overview](#-dashboard-overview)
- [Python Exploratory Data Analysis](#-python-exploratory-data-analysis)
- [Power Query Transformations](#-power-query-transformations)
- [DAX Measures](#-dax-measures)
- [Interactive Dashboard Features](#-interactive-dashboard-features)
- [Business Insights](#-business-insights)
- [Dashboard Snapshots](#-dashboard-snapshots)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

# 📖 Project Overview

This project demonstrates an end-to-end retail sales analysis workflow using **Python**, **Power BI**, **Power Query**, and **DAX**.

The primary objective of this project is to transform raw transactional sales data into meaningful business insights that help stakeholders understand sales performance, customer purchasing behavior, product profitability, and regional trends.

The project consists of two major phases:

- **Python Exploratory Data Analysis (EDA)** for data understanding and statistical exploration.
- **Interactive Power BI Dashboard** for business reporting and decision-making.

The dashboard enables users to interactively analyze business performance through dynamic filters, bookmarks, KPIs, and multiple analytical views.

---

# 🎯 Business Problem

Retail businesses generate thousands of sales transactions every day.

Without proper analysis, it becomes difficult to answer important business questions such as:

- Which products generate the highest revenue?
- Which products are the most profitable?
- Which sales channel performs the best?
- Which regions contribute the highest revenue?
- Which customers generate maximum revenue?
- Which customers contribute the least?
- How do revenue and profit change over time?
- Does unit price influence profit margin?
- Which states require business attention?

This project addresses these questions by transforming raw sales data into an interactive analytical dashboard.

---

# 🎯 Project Objectives

The primary objectives of this project are:

- Perform detailed Exploratory Data Analysis (EDA)
- Identify sales trends over time
- Analyze customer purchasing behavior
- Evaluate product performance
- Measure profitability across channels
- Compare regional sales performance
- Identify top and bottom performing customers
- Create an interactive Power BI dashboard
- Enable business users to explore data through dynamic filters

---

# 📂 Dataset Information

**Dataset Type**

Retail Sales Dataset

**Industry**

Retail / FMCG

**Dataset Source**

Proprietary retail sales dataset (anonymized for analytical and educational purposes).

### Dataset contains information such as:

- Order Number
- Order Date
- Customer Name
- Sales Channel
- Warehouse
- Product Name
- Order Quantity
- Unit Price
- Revenue
- Total Unit Cost
- State
- Region
- County
- Latitude & Longitude
- Median Income
- Budget Information

---

# 🛠 Tools & Technologies

| Category | Tools Used |
|-----------|------------|
| Programming | Python |
| Data Cleaning | Power Query |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Dashboard | Power BI |
| Data Modeling | Star Schema |
| Calculations | DAX |
| Notebook | Jupyter Notebook |
| Version Control | Git & GitHub |

---

# 📁 Repository Structure

```
B2-Mini-Mart-Sales-Analysis
│
├── Dataset
│   └── B2_Mini_Mart.csv
│
├── Python_EDA
│   └── B2_Market_Analysis.ipynb
│
├── Power_BI
│   └── B2_Mini_mart_Analysis.pbix
│
├── Images
│   ├── Executive Summary & Trends.png
│   ├── Executive Summary & Trends - With Filter Button.png
│   ├── Product & Channel Performance.png
│   └── Geographic & Customer Insight.png
│
├── README.md
└── requirements.txt
```

---

# ⚙ Installation

Clone the repository

```bash
git clone https://github.com/YourUsername/B2-Mini-Mart-Sales-Analysis.git
```

Move inside the project directory

```bash
cd B2-Mini-Mart-Sales-Analysis
```

Install required Python libraries

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
B2_Market_Analysis.ipynb
```

To explore the interactive dashboard, open

```
B2_Mini_mart_Analysis.pbix
```

using Microsoft Power BI Desktop.

---

# 🔄 Project Workflow

```
Retail Dataset
        │
        ▼
Data Cleaning (Power Query)
        │
        ▼
Exploratory Data Analysis (Python)
        │
        ▼
Business Insights
        │
        ▼
Power BI Data Modeling
        │
        ▼
DAX Measures
        │
        ▼
Interactive Dashboard
        │
        ▼
Business Decision Making
```

---

# 📦 Python Libraries Used

```python
pandas
numpy
matplotlib
seaborn
jupyter
```

---

# 📊 Dashboard Overview

The Power BI report is divided into **three interactive dashboard pages**, each designed to answer a specific set of business questions.

### Dashboard 1

📈 Executive Summary & Trends

(https://github.com/user-attachments/assets/aac9a566-0f03-4e0a-a782-eeed14d8255f)

Focuses on:

- Overall Business Performance
- Revenue Trends
- Profit Trends
- Revenue Distribution
- Profit Margin Analysis

---

### Dashboard 2

📦 Product & Channel Performance

https://github.com/user-attachments/assets/40627e67-b4cd-48b3-81dc-0602310651c8

Focuses on:

- Best Selling Products
- Most Profitable Products
- Revenue by Channel
- Profit by Channel
- Channel-wise Profit Margin

---

### Dashboard 3

🌍 Geographic & Customer Insight

https://github.com/user-attachments/assets/01bfd183-41e0-4d47-927c-3ff5761b6a7e

Focuses on:

- Top / Bottom Customers
- Regional Revenue
- State-wise Profit
- Geographic Distribution
- Regional Profit Margin

---

# 🐍 Python Exploratory Data Analysis

Before designing the Power BI dashboard, an extensive **Exploratory Data Analysis (EDA)** was performed using **Python** to understand the dataset, identify trends, detect outliers, and uncover hidden business insights.

The analysis was carried out using **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

---

## 📌 Dataset Inspection

The following steps were performed before visualization:

- Loaded dataset using Pandas
- Examined dataset dimensions
- Checked data types
- Generated descriptive statistics
- Identified missing values
- Checked duplicate records
- Validated data consistency

---

## 📊 Distribution Analysis

The objective of this analysis was to understand how numerical variables are distributed throughout the dataset.

The following visualizations were created:

- Revenue Distribution
- Order Quantity Distribution
- Unit Price Distribution
- Median Income Distribution
- Revenue Boxplot

### Key Insights

- Revenue follows a positively skewed distribution, indicating that most transactions generate moderate revenue while a small number contribute significantly higher sales.
- Order quantities are concentrated within a limited range, suggesting consistent purchasing behavior.
- Unit prices are distributed across multiple pricing levels, reflecting different product categories.
- Median income is concentrated around middle-income regions.
- Revenue contains several high-value outliers that may represent premium customers or bulk purchases.

---

---

# 📦 Order Analysis

Order analysis was performed to understand purchasing behavior across different business dimensions.

Visualizations included:

- Orders by Sales Channel
- Orders by Region
- Orders by Warehouse
- Orders by State

### Key Insights

- Wholesale is the dominant sales channel.
- The West region receives the highest number of customer orders.
- Certain warehouses process significantly more orders than others.
- Order distribution varies considerably across states, highlighting regional demand differences.

---

---

# 💰 Revenue Analysis

Revenue analysis focuses on identifying the major revenue contributors.

The following visualizations were created:

- Revenue by Region
- Revenue by Channel
- Revenue by Warehouse
- Top 10 Products
- Top 10 Customers

### Key Insights

- The West region contributes the highest revenue.
- Wholesale generates the largest share of business revenue.
- Revenue is concentrated among a limited number of products.
- A small group of customers contributes a significant percentage of total revenue.

---

---

# 📅 Time Series Analysis

Time-based analysis was performed to identify sales trends and seasonality.

Visualizations included:

- Monthly Revenue Trend
- Monthly Order Trend
- Monthly Quantity Sold
- Monthly Average Unit Price

### Key Insights

- Revenue remains relatively stable throughout the observed period.
- Monthly order volume closely follows revenue trends.
- Product pricing remains consistent over time.
- No major seasonal fluctuations were observed.

---
---

# 📈 Bivariate Analysis

Bivariate analysis was used to examine relationships between key business variables.

The following relationships were analyzed:

- Revenue vs Order Quantity
- Revenue vs Unit Price
- Revenue vs Median Income
- Unit Price vs Order Quantity

### Key Insights

- Revenue generally increases with higher order quantities.
- Higher-priced products tend to generate higher revenue.
- Median income has a relatively weak relationship with revenue.
- Unit price does not strongly influence order quantity.

---
---

# 🔥 Correlation Analysis

Correlation analysis was performed to understand relationships between numerical variables.

A correlation heatmap was generated using Pearson Correlation.

### Variables Included

- Revenue
- Order Quantity
- Unit Price
- Total Unit Cost
- Median Income
- Budget

### Key Insights

- Revenue has a strong positive correlation with Unit Price.
- Revenue is also positively correlated with Total Unit Cost.
- Median Income has little influence on Revenue.
- Order Quantity has a moderate impact on Revenue.

---
---

# 🌍 Geographic Analysis

Geographical analysis helps understand regional business performance.

The following analyses were performed:

- Revenue by Region
- Top States by Revenue
- Customer Distribution by Region
- Geographic Revenue Distribution

### Key Insights

- The West region consistently outperforms other regions.
- Certain states contribute significantly more revenue than others.
- Customer concentration varies across regions, indicating differences in market demand.

---
---

# 🔄 Data Cleaning & Power Query Transformations

Before building the dashboard, the dataset was cleaned and transformed using **Power Query**.

The following transformations were performed:

- Changed incorrect data types
- Converted Order Date into Date format
- Extracted Month Name
- Extracted Year
- Handled missing values
- Renamed columns for better readability
- Removed unnecessary columns
- Validated null values
- Standardized text formatting
- Prepared the dataset for reporting

These transformations ensured data consistency and improved dashboard performance.

---

# 📊 Power BI Dashboard

The Power BI report consists of **three fully interactive dashboard pages**, designed to answer different business questions.

---

# 📈 Dashboard 1 — Executive Summary & Trends

This dashboard provides a high-level overview of overall business performance.

### KPI Cards

- Total Revenue
- Total Profit
- Profit Margin %
- Total Orders
- Revenue Per Order

### Visualizations

- Monthly Revenue Trend
- Monthly Profit Trend
- Revenue Distribution
- Profit Margin Distribution
- Revenue vs Profit Scatter Plot

### Business Questions Answered

- How is the business performing overall?
- Is revenue increasing over time?
- What is the current profit margin?
- How many orders have been processed?
- What is the average revenue generated per order?

---

### Dashboard Snapshot

```
https://github.com/user-attachments/assets/aac9a566-0f03-4e0a-a782-eeed14d8255f
```

---

# 📦 Dashboard 2 — Product & Channel Performance

This dashboard focuses on identifying top-performing products and sales channels.

### Visualizations

- Top 5 Products by Revenue
- Top 5 Products by Profit
- Revenue by Channel
- Profit by Channel
- Profit Margin by Channel
- Revenue vs Profit Analysis

### Business Questions Answered

- Which products generate the highest revenue?
- Which products are the most profitable?
- Which sales channel contributes the most revenue?
- Which channel delivers the highest profit margin?

---

### Dashboard Snapshot

```
https://github.com/user-attachments/assets/40627e67-b4cd-48b3-81dc-0602310651c8
```

---

# 🌍 Dashboard 3 — Geographic & Customer Insight

This dashboard provides customer and regional performance analysis.

### Visualizations

- Top / Bottom Customers
- Top / Bottom States
- Revenue by Region
- Profit Margin by Region
- Geographic Revenue Map

### Business Questions Answered

- Which customers generate the highest revenue?
- Which customers require attention?
- Which regions perform the best?
- Which states have lower profitability?
- How is revenue distributed geographically?

---

### Dashboard Snapshot

```
https://github.com/user-attachments/assets/01bfd183-41e0-4d47-927c-3ff5761b6a7e
```

---

# 🎯 Interactive Features

To improve user experience and dashboard usability, several interactive features were implemented.

### ✔ Dynamic Filter Panel

A bookmark-driven filter panel allows users to show or hide slicers without occupying dashboard space.

### ✔ Bookmarks

Bookmarks were used to:

- Show / Hide Filters
- Switch between Top 5 and Bottom 5 analyses
- Improve navigation experience

### ✔ Cross Filtering

Selecting any visual automatically filters the remaining visuals on the report page.

### ✔ Interactive Slicers

Users can filter the report using:

- Region
- State
- Sales Channel
- Warehouse
- Product
- Customer
- Year

making the dashboard highly interactive and user-friendly.

---

# 🧮 DAX Measures

Although the dashboard primarily utilizes existing dataset fields, several DAX measures were created to enhance business reporting.

The following measures were implemented:

### Total Revenue

```DAX
Total Revenue = SUM(B2_Mini_Mart[Revenue])
```

---

### Total Profit

```DAX
Total Profit =
SUM(B2_Mini_Mart[Revenue]) -
SUM(B2_Mini_Mart[total_unit_cost])
```

---

### Profit Margin %

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Revenue]
) * 100
```

---

### Revenue Per Order

```DAX
Revenue Per Order =
DIVIDE(
    [Total Revenue],
    DISTINCTCOUNT(B2_Mini_Mart[ordernumber])
)
```

---

# 📊 Dashboard Features

The Power BI dashboard was designed with business users in mind and includes several interactive features.

## Executive KPI Cards

The dashboard provides quick insights into:

- Total Revenue
- Total Profit
- Profit Margin
- Total Orders
- Revenue Per Order

---

## Dynamic Filtering

Users can filter the dashboard by:

- Region
- State
- Warehouse
- Sales Channel
- Product
- Customer
- Year

---

## Interactive Bookmarks

Bookmarks were implemented to improve user experience.

Features include:

- Show/Hide Filter Panel
- Top 5 vs Bottom 5 Customer Analysis
- Smooth dashboard navigation

---

## Cross Filtering

Every visual interacts with the remaining visuals on the page, enabling users to drill into specific business segments effortlessly.

---

## Responsive Dashboard Design

The report layout was designed to maximize readability while maintaining a clean and professional appearance.

---

# 📷 Dashboard Snapshots

## Executive Summary & Trends

```
https://github.com/user-attachments/assets/aac9a566-0f03-4e0a-a782-eeed14d8255f
```

---

## Executive Summary with Dynamic Filter Panel

```
https://github.com/user-attachments/assets/c9f080ff-6585-4eec-9418-154648d8ce5c
```

---

## Product & Channel Performance

```
(https://github.com/user-attachments/assets/40627e67-b4cd-48b3-81dc-0602310651c8)
```

---

## Geographic & Customer Insight

```
https://github.com/user-attachments/assets/01bfd183-41e0-4d47-927c-3ff5761b6a7e
```

---

# 💡 Business Insights

The analysis revealed several valuable business insights.

---

## Revenue Performance

- The business generated over **₹1.24 Billion** in total revenue.
- Overall profit exceeded **₹460 Million**.
- Profit margin remained healthy at approximately **37%**.

---

## Product Performance

- A limited number of products contribute a significant percentage of total revenue.
- High-performing products should receive priority for inventory planning and promotional campaigns.
- Low-performing products require pricing or marketing strategy evaluation.

---

## Customer Analysis

- Revenue is concentrated among a relatively small number of customers.
- Identifying and retaining these high-value customers can significantly improve long-term profitability.
- Bottom-performing customers may represent opportunities for customer engagement initiatives.

---

## Regional Performance

- Certain regions consistently outperform others in terms of revenue generation.
- Regional sales differences indicate opportunities for targeted marketing campaigns.
- Geographic analysis helps identify underperforming markets requiring additional business attention.

---

## Sales Channel Analysis

- Wholesale contributes the largest share of total business revenue.
- Different sales channels demonstrate varying profit margins.
- Understanding channel performance helps optimize sales strategy.

---

## Revenue Trends

- Monthly revenue remains relatively stable over time.
- Revenue fluctuations closely align with order volume.
- No significant seasonal variations were observed within the available dataset.

---

# 📈 Skills Demonstrated

This project demonstrates practical experience across multiple stages of the data analytics lifecycle.

## Python

- Data Cleaning
- Data Manipulation
- Exploratory Data Analysis
- Data Visualization

---

## SQL Concepts Applied

- Business-oriented data analysis
- Aggregation techniques
- Ranking logic
- Analytical thinking

---

## Power Query

- Data Cleaning
- Data Transformation
- Data Type Conversion
- Date Transformations
- Feature Engineering

---

## Power BI

- Interactive Dashboard Development
- KPI Design
- Data Modeling
- Visual Analytics
- Report Design
- Bookmarks
- Dynamic Navigation
- Filter Pane Design

---

## DAX

- Measures
- Aggregations
- Mathematical Calculations
- Business KPIs

---

## Data Visualization

- Bar Charts
- Line Charts
- Scatter Charts
- Maps
- KPI Cards
- Slicers
- Interactive Filters

---

# 🚀 Future Improvements

Potential enhancements for future versions include:

- Sales Forecasting using Machine Learning
- Customer Segmentation (RFM Analysis)
- Customer Lifetime Value (CLV) Analysis
- Inventory Optimization Dashboard
- Profit Forecasting
- Automated Data Refresh
- Integration with SQL Database
- Deployment to Power BI Service
- Mobile Dashboard Optimization

---


---

# 🎯 Learning Outcomes

Through this project, I strengthened my understanding of:

- End-to-End Data Analytics Workflow
- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Business Intelligence Reporting
- Interactive Dashboard Design
- DAX Calculations
- Business-Oriented Storytelling
- Data-Driven Decision Making

---

# 📌 Conclusion

This project demonstrates an end-to-end analytics workflow, starting from raw retail sales data and progressing through data cleaning, exploratory analysis, and interactive dashboard development.

By combining Python for in-depth analysis and Power BI for business reporting, the project transforms raw transactional data into actionable insights that can support informed business decisions.

It highlights not only technical proficiency with modern analytics tools but also the ability to communicate data effectively through intuitive visualizations and meaningful business narratives.

---

---

# 🚀 Why This Project?

This project was built to strengthen my practical knowledge of data analytics by applying industry-standard tools and techniques to a real-world retail dataset.

Rather than focusing only on visualizations, the project emphasizes the complete analytics lifecycle:

- Understanding business requirements
- Cleaning and preparing raw data
- Performing exploratory data analysis
- Identifying meaningful business insights
- Designing interactive dashboards
- Communicating findings effectively
---

# 👨‍💻 Author

**Aman Jaiswal**

Aspiring Data Analyst | Python | SQL | Excel | Power BI | Tableau

I enjoy transforming raw data into meaningful insights and building interactive dashboards that support data-driven decision-making.

Feel free to connect with me on LinkedIn and explore more of my projects on GitHub.

---
# 📬 Feedback

I would greatly appreciate any feedback or suggestions that could help improve this project.

If you have recommendations regarding:

- Dashboard Design
- Python Code
- Power BI Best Practices
- DAX Optimization
- Data Storytelling

feel free to open an issue or connect with me.

---

# ⭐ Support

If you found this project interesting or useful:

⭐ Star this repository

🍴 Fork the repository

📢 Share your feedback

Every suggestion helps me improve as a Data Analyst.

---

## Thank You for Visiting!

Thank you for taking the time to explore this project.

I hope it demonstrates my ability to work across the complete data analytics pipeline—from raw data to actionable business insights.

Happy Analyzing! 📊
