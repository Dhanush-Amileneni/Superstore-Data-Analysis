
SALES PERFORMANCE & REVENUE INSIGHTS DASHBOARD

PROJECT OVERVIEW
This project is an end-to-end data analytics solution that analyzes sales performance using the Superstore dataset.
It covers the complete analytics lifecycle — from raw data ingestion and cleaning using Python to building
interactive business dashboards in Power BI Web.

The goal of this project is to provide actionable business insights into revenue, profit, regional performance,
product profitability, and the impact of discounts on profit.


BUSINESS QUESTIONS ANSWERED
- How are revenue and profit trending over time?
- Which regions contribute the most to revenue and profit?
- What are the top 10 most profitable products?
- Which products are causing losses?
- How do discounts impact profit?
- What are the key KPIs driving business performance?


TECH STACK
- Python (Pandas, NumPy) – Data cleaning & transformation
- Jupyter Notebook (.ipynb) – Exploratory analysis & preprocessing
- Power BI (Web) – Data modeling & dashboard visualization
- GitHub – Version control & project documentation


PROJECT STRUCTURE
Sales-Performance-Analysis/
│
├── data/
│   ├── Superstore.csv
│   └── superstore_cleaned.csv
│
├── notebooks/
│   └── cleaning_data.ipynb
│
├── powerbi/
│   └── Sales_Performance_Dashboard.pdf
│
├── screenshots/
│   ├── revenue_profit_trend.png
│   ├── revenue_profit_by_region.png
│   ├── top_10_products_profit.png
│   ├── bottom_10_loss_products.png
│   └── discount_vs_profit.png
│
└── README.txt


END-TO-END WORKFLOW

1. DATA EXTRACTION
- Imported the raw Superstore.csv dataset.
- Verified schema, data types, and record counts.

2. DATA CLEANING & TRANSFORMATION (Python)
Performed in cleaning_data.ipynb:
- Standardized column names
- Converted date columns to datetime
- Removed duplicates
- Validated numeric fields (Sales, Profit, Discount, Quantity)
- Handled invalid and missing values
- Created derived metrics:
  - Profit Margin
  - Average Order Value (AOV)

Exported the cleaned dataset as:
superstore_cleaned.csv


3. DATA VISUALIZATION (Power BI Web)
Built an interactive dashboard with the following visuals:

KPI CARDS
- Total Revenue
- Total Profit
- Profit Margin
- Average Order Value (AOV)

TREND ANALYSIS
- Revenue & Profit over time (Order Date)

REGIONAL PERFORMANCE
- Revenue & Profit by Region

PRODUCT ANALYSIS
- Top 10 Products by Profit
- Bottom 10 Loss-Making Products

DISCOUNT ANALYSIS
- Discount vs Profit (Scatter Plot)


DASHBOARD PREVIEW
The final Power BI dashboard is exported as a PDF:
powerbi/Sales_Performance_Dashboard.pdf

Individual visual screenshots are available in the screenshots folder for quick review.


KEY INSIGHTS
- The West region generates the highest revenue and profit.
- A small number of products contribute disproportionately to total profit.
- Heavy discounts are often correlated with negative profit, indicating pricing risks.
- Some high-selling products are loss-making, highlighting optimization opportunities.


KEY TAKEAWAYS
- Demonstrates a real-world data analytics workflow
- Combines Python and BI tools effectively
- Focuses on business-driven insights
- Suitable for Data Analyst and Business Analyst roles


FUTURE IMPROVEMENTS
- Add customer segmentation analysis
- Forecast sales using time series models
- Build a star schema data model
- Publish dashboard using Power BI Service sharing options


AUTHOR
Dhanush Amileneni
Graduate in Computer Science
Aspiring Data Analyst / Data Engineer
