# Sales-Data-Analysis
(Please refer to the Python_Code_Sales_Project.ipynb for comprehensive insights, exploratory data analysis (EDA), detailed explanations, recommendations, and various visualizations.)
# Overview
This project analyzes a Kaggle “Superstore” dataset to answer:  
- Which products are the top sellers?  
- Which regions or customer segments generate the most profit?  
- What are the monthly / seasonal sales trends?

# 1. Objectives
-Sales by Category: Examine the total sales over different products
-Profit by Region: Calculate the total profit over different regions such as North, South, East and West region
-Top 10 Products: Investigate Top 10 products sold
-Sales over Time: Identify monthly sales trend

# 2. Methodology
   # 2.1 Data Preparation: 
   Cleaned the dataset by checking the missing values, removed the duplicates, fixed the data    
   types, removed outliers to check extreme values in Sales or Profit and confirmed the clean-  
   up.
   
   # 2.2 Feature Engineering 
   Derived "Month-Year" from the date for trend analysis.  
   
   # 2.3 Exploratory Data Analysis (EDA):   
   # Top-selling products: Top 10 products by sales and Total sales and profit by product category 
         -Grouped the data by product name         
         -Calculated total sales for each product         
         -Sort the products in descending order   

  # To investigate profit by region: Profit by region  
         -Grouped the data by region
         -Calculated total profit for each region
         -Selected the region with the highest profit
         -This helped identify which regions generated the highest profitability and which underperformed.   

  #  To identify sales trend over time: Time series analysis of monthly sales and profit
         •	Converted dates into a monthly (Month-Year) format
         
         •	Calculated total sales for each month
         
         •	Sorted the months in chronological order
         
         •	This analysis highlighted seasonal patterns, spikes in demand, and months with lower performance.  

# 3. Visualizations
•	Aggregated sales by Month-Year to create a monthly sales trend analysis. This helped identify seasonal patterns, monthly fluctuations, and overall sales growth.

•	Calculated total profit for each region to compare financial performance across geographic areas. This analysis revealed which regions contributed the most profit and which underperformed.

•	Summarized the dataset by counting the number of orders in each product category. This analysis highlighted which categories were most frequently purchased and which had lower order volumes.

•	Ranked all products by total sales and selected the top 10 highest-performing items. This highlighted which products generated the most revenue and drove overall sales performance.

# 4. Key Insights
- The top 10 products (by sales) contributed **12.4%** of total revenue  
- The **West** region has the highest profit margin  
- There is a **seasonal trend**: sales peak in **November** and dip in **June**
  
# Added KPIs with Results
- Total Sales = SUM(Sales) = **$2.3M**
- Total Profit = SUM(Profit)= **$290K**
- Profit Margin = Profit / Sales= **12.4%**
  
# 6. Conclusion 
The sales data analysis revealed clear patterns in product performance, regional profitability, and monthly sales trends. These insights can help guide better decision-making in forecasting, inventory planning, and targeting high-value markets. 
 


