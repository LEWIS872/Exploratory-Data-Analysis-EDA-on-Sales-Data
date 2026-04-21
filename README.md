# Project Title: GlobalMart Sales Analysis:Exploratory Data Analysis (EDA) 
 GlobalMart is a large international retail chain company that wants to understand its sales performance across different regions, product categories, and time periods. Perform an exploratory data analysis on the company's sales data to uncover insights that can drive business decisions.
## Table of Contents
- [Overview] ( #Overview)
  
- [Data set] ( #Datasets)
  
- [Technologies Used] ( #Technologies used)
  
- [Installation] ( #Installation)
  
- [Usages] ( #Usages)
  
- [Analysis&Visualization] (#Analysis & Visualization)
  
- [Conclusion] ( #Conclusion)
  
- [Credits] ( #Credits)
  
- [License] ( #License)

## Overview
This project performs an exploratory data analysis(EDA) on GlobalMart's retail sales data to uncover insights into sales performance, profitability, product trends, and regional distribution. The analysis aims to support data-driven decision-making in areas such as product strategy, pricing, and regional performance optimisation.
   
## Objectives:
            1. Analyse overall Sales and Profit performance

            2.Identify top-performing products and regions.
            
            3.Examine relationships between sales, profit, and discount
            
            4.Explore time-based sales trends and seasonality

            5.Provide actionable insights for business decision-making.
            
## Tools and Technologies
Python
pandas
Numpy
Matplotlib
Seaborn
Statsmodels
JupyterNotebook

## Datasets
- Source of Dataset: Global Superstore Dataset (available on Kaggle)
- Size of Dataset: (1000,24)

  ## Data Preparation
  1.Loaded dataset from CSV file
  2.Checked for missing values and removed incomplete records
  3.Converted date columns(Order Date, Ship Date) into datetime format
  4.Created new time-based features(monthly sales)
  5.Ensured numerical consistency for key variables(Sales, Profit, Discount)

  ## Key Metrics
  1.Total Sales: 54,535.08
  2.Total Profit: 12,063.97

  ## Exploratory Data Analysis & Insights
  # Top Performing Products
  The Analysis identified the top 10 products by total sales. Binding systems and office equipment dominate the highest revenue-generating products, indicating strong demand in this category.

  # Sales by Region
  1.Central US and Western US generate the highest sales
  2.Southern US shows comparatively lower performance
  This suggests regional variation in market demand and potential opportunities for  growth in underperforming regions.

  # Sales Vs Profit Relationship
  Strong positive correlation(r = 0.93) between sales and profit.
  Higher Sales generally lead to higher profitability, indicating efficient cost and pricing structures.

  # Discount Vs Profit Relationship
  Weak negative correlation(r = -0.16)
  Increased discounting slightly reduces profitability, suggesting that aggressive discount strategies may not always be beneficial.

  # Sales by Product Category
  Bar plot analysis shows variation in sales across Categories, highlighting which product segments drive revenue.

  # Monthly Sales Trends
  1.Sales fluactuate over time with observable patterns.
  2.Seasonal decomposition indicates trend and seasonal components
  This insight can support demand forecasting and inventory planning

  # Sales Vs Profit(Scatter plot)
  1. Positive linear relationship between sales and profit
  2. Few outliers indicate cases where high sales and did not translate into proportional profit

  # Regional and Category Performance(Heatmap)
  1.Heatmap reveals differences in sales distribution across regions and product Categories
  2.Identifies strong and weak combinations for strategies focus

  # Key Findings
  1. Sales and profits are strongly positively correlated
  2. Discounting has a slight negative impact on profitability
  3. Certain products significantly outperform others in revenue generation
  4. Regional performance varies, with Central and Western regions leading
  5. Sales show temporal patterns, indicating seasonality
  6. Some high-sales transactions yeild lower profit, suggesting pricing inefficiencies.

  # Implications
  1.High performing products should be priotised in inventory and marketing strategies
  2.Discount strategies should be carefully managed to protect profit margins
  3.Underperforming regions present opportunities for targeted growth strategies
  4. Seasonal trends can inform demand forecasting and supply chain planning
  5.Pricing strategies may need refinement for certain products

  # Recommendations
  1. Focus marketing efforts on top-performing products to maximise revenue
  2. Optimise discount policies to balance sales growth and profitability
  3. Investigate and improve performance in underperforming regions
  4. Leverage seasonal trends for better inventory and resource planning
  5. Analyse low-profit transactions to improve pricing and cost efficiency

  # Conclusion
  The analysis provides valuable insights in GlobalMart's sales and profitability dynamics. Strong relationships between sales and profit highlights effective business operations, while the impact of discounting and regional variation revals oppotunities for optimisation. By leveraging these insights, the organization can make informed decisions to enhance revenue growth and operational efficiency.




