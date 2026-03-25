# Superstore Sales Analysis

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

A retail sales analysis of 5,009 orders where I went beyond the surface numbers to find what the business was actually missing. Built end to end in Python -from raw messy data to clean insights and business recommendations.


# Why I Built This

I wanted to work on something that felt real. Not a tutorial. Not a walkthrough. An actual dataset with actual problems that needed actual thinking.
The data came in messy. Missing values, broken date formats, inconsistent text columns. I cleaned all of it before writing a single line of analysis. That cleaning process alone taught me more than any tutorial ever did.


## What The Data Revealed

**The Tables problem**

Tables is one of the store's active product lines. It sells regularly. Customers buy it. But after running the numbers, every single Tables transaction is pulling profit down. The sales look fine on the surface. The profit tells a completely different story. This is the exact kind of gap that goes unnoticed until it becomes a very serious problem.


**The discount trap**

The correlation between discount and profit in this dataset is -0.219. The moment a discount crosses 20%, average profit flips negative. What the business probably calls a customer retention strategy is quietly costing money on each of those orders.


**Two peaks**

November generates the highest total revenue. Makes sense - holiday season, more orders, more volume. But March has the highest average order value. Customers in March spend more per order than any other month. 


## Numbers At A Glance

| Metric | Value |
|---|---|
| Total Orders | 5,009 |
| Unique Customers | 793 |
| Total Sales | $2,297,201 |
| Total Profit | $286,397 |
| Profit Margin | 12.5% |
| Best Performing Region | West |
| Top Revenue Category | Technology |
| Loss Making Sub-Category | Tables |
| Peak Revenue Month | November |
| Peak Avg Order Month | March |
| Discount vs Profit Correlation | -0.219 |


## Business Recommendations From me

Based on what the data showed, here is what I would tell the business:

1. **Investigate Tables immediately** — the profit numbers say this product 
   line is a problem. Either renegotiate supplier costs or reconsider the 
   line entirely. Ignoring it is expensive.

3. **Cap all discounts at 20%** — anything above that is a loss per order. 
   The data makes this very clear and the business should treat it as a hard rule.

4. **Invest more in the West region** — it leads consistently across all 
   categories and has the strongest growth potential of the four regions.

5. **Double down on Technology** — top category by both sales and profit margin. 
   More budget here has a direct and measurable return.

6. **Start November planning early** — it is the peak revenue month and it 
   needs peak level preparation. Last minute campaigns will not cut it.


## Charts From The Analysis

![Sales by Category](chart1_category_sales.png)
![Sales vs Profit](chart2_sales_vs_profit.png)
![Sales by Region](chart3_region_sales.png)
![Monthly Trend](chart4_monthly_trend.png)
![Sub-Category Profit](chart5_subcategory_profit.png)
![Discount vs Profit](chart6_discount_profit.png)


## Project Structure

| File | What It Contains |
|---|---|
| `superstore_analysis.ipynb` | Full analysis notebook with all code and outputs |
| `superstore_cleaned.csv` | Cleaned and processed dataset |
| `chart1_category_sales.png` | Total sales broken down by category |
| `chart2_sales_vs_profit.png` | Sales and profit comparison side by side |
| `chart3_region_sales.png` | Regional sales performance breakdown |
| `chart4_monthly_trend.png` | Monthly sales trend with peak markers |
| `chart5_subcategory_profit.png` | Profit and loss across all sub-categories |
| `chart6_discount_profit.png` | How discount levels impact profit |


## Tools and Libraries

| Tool | Purpose |
|---|---|
| Python 3.12 | Core language for the entire analysis |
| Pandas | Data loading, cleaning and manipulation |
| Matplotlib | Building and styling all visualizations |
| Seaborn | Chart aesthetics and theme |
| Jupyter Notebook | Development and documentation environment |


## Skills This Project Covers

- Real world data cleaning from scratch
- Exploratory data analysis
- Feature engineering from existing columns
- Business insight extraction from raw numbers
- Data storytelling through visualization


## Dataset

**Source:** Kaggle - Sample Superstore Dataset  
**License:** CC0 Public Domain  
**Size:** 9,994 records across 4 regions, 3 product categories and 4 years  


## About

I am Md Istiak Hossain and I am building my skills in business data analytics. 
There are more projects on the way.

**LinkedIn:** [Connect with me]https://www.linkedin.com/in/istiak-hossain-/
