# 📌 Overview
This project analyzes the Sample Superstore dataset to evaluate sales performance, profitability, discount impact, and regional trends.

### The analysis was conducted using:
- Python (Pandas, Matplotlib)
- Power BI (Executive Dashboard)
- Data Cleaning & Transformation
### The goal is to identify:
- Which categories generate the most revenue
- Which sub-categories are most profitable
- The impact of discounts on profit
- Regional performance differences
- High-risk loss areas

# 📑 Table of Contents
1. Dataset Description
2. Column Definitions
3. Tools Used
4. Python Data Analysis
5. Power BI Dashboard
6. Key Insights
7. Conclusion

# 📂 Dataset Description
### The dataset used is the Sample Superstore dataset, containing transactional sales data including:
- Customer segments
- Geographic location
- Product category & sub-category
- Sales
- Quantity
- Discount
- Profit
- Total records: 9,977 rows
- Total columns: 13

# 🧾 Column Definitions
|Column|Description|
|------|-----------|
|Ship Mode|Shipping method used|
|Segment|Customer segment (Consumer, Corporate, Home Office)|
|Country|Country of order|
|City|City of order|
|State|State of order|
|Postal|Code	ZIP code|
|Region|Sales region (East, West, Central, South)|
|Category|Product category|
|Sub-Category|Product sub-category|
|Sales|Revenue generated|
|Quantity|Units sold|
|Discount|Discount applied (percentage)|
|Profit|Net profit per transaction|

### Additional engineered columns:
- Profit Margin %
- Discount Level (No Discount, Low, Medium, High)
- Loss Flag (Profit/Loss indicator)

# 🛠 Tools Used
- Microsoft Excel – Data preparation and structured dataset management
- Python (Pandas, Matplotlib) – Data cleaning, transformation, and exploratory data analysis (EDA)
- Power BI – Interactive executive dashboard and KPI reporting
- GitHub – Version control and project documentation

# 🐍 Python Analysis (Charts & Description)
### Below are the main visualizations created using Pandas & Matplotlib.

## 1. Total Sales by Category
### Shows revenue distribution across product categories.
<img width="1767" height="1166" alt="total_sales_by_category" src="https://github.com/user-attachments/assets/66d91cf7-d4e1-4e41-a4ff-ff719067c8e7" />

## Finding:
- Technology generates the highest sales, followed by Furniture and Office Supplies.

## 2. Total Profit by Category
### Analyzes profitability per category.
<img width="1767" height="1166" alt="total_profit_by_category" src="https://github.com/user-attachments/assets/8b65229b-6d1c-4c23-a19e-f05716fcbb0a" />

## Finding:
- Technology is the most profitable category.
- Furniture generates high sales but lower profit margin.

## 3. Profit by Region
### Compares regional performance.
<img width="1767" height="1167" alt="profit_by_region" src="https://github.com/user-attachments/assets/47905f1c-b4c1-4693-9746-a8650ef4f18c" />

## Finding:
- West region leads in total profit.
- Central region performs the weakest.

## 4. Profit by Discount Level
### Shows the relationship between discount levels and profitability.
<img width="1767" height="1167" alt="profit_by_discount_level" src="https://github.com/user-attachments/assets/f5f291b4-5bea-465d-bf9b-9981ac16cc2e" />

## Finding:
- No Discount → Highest profit
- Low Discount → Still profitable
- Medium & High Discount → Negative profit
### This confirms that excessive discounting damages profitability.

## 5. Top 10 Sub-Categories by Profit
### Identifies best performing products.
<img width="2067" height="1467" alt="top_10_subcategories_profit" src="https://github.com/user-attachments/assets/c90a1278-6e85-4b02-b28c-4d8b197d5581" />

## Top contributors include:
- Copiers
- Phones
- Accessories
- Paper

## 6. Bottom 10 Sub-Categories by Profit
### Identifies loss-generating products.
<img width="2067" height="1467" alt="bottom_10_subcategories_profit" src="https://github.com/user-attachments/assets/48322e1c-2801-41b2-bcf0-02d71a8c9087" />

## Major losses come from:
- Tables
- Bookcases
- Supplies

# 📊 Power BI Executive Dashboard
## The dashboard contains:

### KPI Cards
- Total Sales
- Total Profit
- Total Quantity
- Profit Margin %

### Interactive Filters
- Region
- Category
- Segment

### Visualizations
- Sales by Category
- Profit by Region
- Profit by Category
- Top Sub-Categories
- Loss Sub-Categories
- Profit by Discount Level

### Features
- Conditional formatting (red for negative profit)
- Clean executive layout
- Professional color palette
- Interactive slicing

# 🔍 Key Insights
1. Technology drives the majority of both sales and profit.
2. High discount levels directly cause losses.
3. West region performs strongest overall.
4. Some products generate revenue but destroy profit (e.g., Tables).
5. Profit margin decreases significantly when discount exceeds 20%.
6. Not all high-sales products are profitable.

# 📌 Conclusion
## This analysis highlights the importance of:
- Controlled discount strategies
- Regional performance monitoring
- Category-level profit evaluation
- Focusing on high-margin sub-categories
 
### The combination of Python (for deep analysis) and Power BI (for executive visualization) provides a complete data analysis workflow.

# 🚀 Project Outcome
- Cleaned & analyzed 9,977 records
- Built automated visualizations in Python
- Designed executive Power BI dashboard
- Identified high-risk discount strategy
- Extracted actionable business insights
