  # Sales-Data-Analysis

(Please refer to the xyz.ipynb for comprehensive insights, exploratory data analysis (EDA), detailed explanations, recommendations, and various visualizations.)

Overview
This project focusses on analyzing the sales in different regions using a comprehensive Kaggle Superstore dataset. The objective is to identify which products were sold the most, which regions or customer segments are most profitable and what are the monthly/seasonal trends in sales and profit.

1. Objectives
 Sales by Category: Examine the total sales over different products
 Profit by Region: Calculate the total profit over different regions such as North, South, East and   
 West region
 Top 10 Products: Investigate Top 10 products sold
 Sales over Time: Identify monthly sales trend

3. Methodology
    Data Preparation: Cleaned the dataset by checking the missing values, removed the duplicates, fixed the data    
   types, removed outliers to check extreme values in Sales or Profit and confirmed the clean-  
   up.
 
   Exploratory Data Analysis (EDA): Extracted year and month for trend analysis and verified new columns
   Analyzed the sales and profit data by generating summary statistics, including totals,averages, and distribution metrics. 
   The results offered a comprehensive view of financial performance across products and periods.
   
    To obtain the top-selling products:
           Grouped the data by product name
           Calculated total sales for each product
           Sort the products in descending order
    
    To investigate profit by region:
           Grouped the data by region
           Calculated total profit for each region
           Selected the region with the highest profit
           This helped identify which regions generated the highest profitability and which 
            underperformed.
   
    To identify sales trend over time:
       Converted dates into a monthly (Month-Year) format
       Calculated total sales for each month
       Sorted the months in chronological order
       This analysis highlighted seasonal patterns, spikes in demand, and months with lower 
        performance.
  
5. Visualizations
    Aggregated sales by Month-Year to create a monthly sales trend analysis. This helped identify seasonal patterns, monthly fluctuations, and overall sales growth.
   Calculated total profit for each region to compare financial performance across geographic 
    areas. This analysis revealed which regions contributed the most profit and which 
   underperformed.
  Summarized the dataset by counting the number of orders in each product category. This   
  analysis highlighted which categories were most frequently purchased and which had lower 
  order volumes.
  Ranked all products by total sales and selected the top 10 highest-performing items. This   
  highlighted which products generated the most revenue and drove overall sales performance.

6. Insights
    Identified the top-performing product by ranking all products based on their total sales, with the highest-selling item. Visualized it through a bar graph with product name and total sales
    The most profitable region showed the greatest contribution to overall profit, indicating stronger market demand or better operational efficiency in that area. Visualized it by a bar chart with region and         total profit

7. Built visuals for:
    Sales by Category (bar)
    Profit by Region (map)
    Monthly Sales Trend (line)
    Top Products by Sales (bar)

  Added KPIs with Results
    Total Sales = SUM(Sales) = $2.3M
    Total Profit = SUM(Profit)= $290K
    Profit Margin = Profit / Sales= 12.4%

6. Conclusion
    The sales data analysis revealed clear patterns in product performance, regional profitability, and monthly sales trends. These insights can help guide better decision-making in forecasting, inventory             planning, and targeting high-value markets.

