# Superstore Sales Analysis
### 1. Objective 
This project aims to analyze superstore sales and customer transaction data over the span of 5years (2014, 2015, 2016, 2017, 2018) in order to drive insights regarding high-demand products, regions with most demanding customers, and determine how to further increase sales and prevent decline, while maintaining customer base and increasing repeating customers.

### 2. Dataset 
- Source: Kaggle [(Superstore Dataset)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- Contains information on customers' transaction data such as order date, ship date, product category/subcategory, quantity sold, sales amount, and customer's demographics.
- Contain about 10k transaction records.

### 3. Tools & Technologies 
- Power Query (Data cleaning and transformation)
- DAX (Data modelling and summarization)
- Power BI (Data visualization and dashboards interactivity) 

### 4. Data Cleaning 
- Removed non-informative columns such as row identifier and postal code.
- Standardized column names and data types.
- Normalized text columns
- Created calculated columns for efficient analysis.
- Created DAX measures such as Profit and Revenue -------

### 5. Data Modeling 
The data was structured using a star schema with FactOrders as the fact table, connected to dimension tables of customers, products, and date data. 

### 6. Business Questions 
- Which product category/subcategory achieved the highest sales?
- Which product category/subcategory achieved the lowest sales
- which products (subcategory) had the least sales and demand?
- which city had the highest demand and sales?
- which city had the least demand and sales?
- Which customer segment provides higher sales?
- How is sales and order frequency affected over seasons/time?
- what is the % of profit out of the achieved sales?
- What is the % of returning customers?

### 7. Analysis 
- Compared profit to cost %
- Compared the profitability of different product categories and subcategories
- Analyzed time and seasonal effects on sales and orders frequency.
- Investigated demographics effects on sales.
- Identified sales share of different customer segments.

### 8. Visualization 
#### [General Overview](https://github.com/noura-tarek-m/superstore-sales/blob/master/project-images/1.png)
An executive summary of the following main KPIs: Total sales, cost, and profit margin.

#### [Dashboard One: Sales](https://github.com/noura-tarek-m/superstore-sales/blob/master/project-images/2.png)
This dashboard shows yearly sales, monthly sales and quantities trends, and sales share of different shipping mode. It shows important KPIs such as total quantity sold and average quantity per order. it can help determine the year with highest sales through out the period 2014~2017, months/seasons with higher sales, and reliable shipping modes 

#### [Dashboard Two: Product](https://github.com/noura-tarek-m/superstore-sales/blob/master/project-images/3.png)
This dashboard contains the achieved sales per each category, products or subcategories that had the least and highest sales, and displays products-related KPIs such as average price per unit and average unit cost. we can determine most-demanded products category, and products that had the least demands from the dashboard.

#### [Dashboard Three: Customer](https://github.com/noura-tarek-m/superstore-sales/blob/master/project-images/4.png)
the dashboard shows the demographics data of customers, it shows the sales achieved from different cities across US, sales share of customer segments, and total sales achieved and quantites sold for each region in the country. important KPIs displayed are total customers, repeat customers and return rate. this can help determine the % of loyal customers and our targeted customer segment. 
slicers are used across the three dashboards to introduce interactivity and better explore data across different time ranges and locations.
 
### 9. Key Findings (Insights) & Recommendations 
1.	Out of the acieved sales, only 15% is the profit margin. this indicates that the total cost is too high that sales are barely covering it. strategies should be taken to significantly cut down total costs.
2.	March, September, and November are the highest performing months. the store should maintain adequat inventory levels and ensure products availability during these periods.
3.	Most sales are achieved from orders delivered by standard shipping mode.
4.	Technology products achieved the higest sales, phones, specifically. on the other hand, office supplies are of higher-demand. Furniture had the highest costs.
5.	most sales comes from California, New York comes in second place. cities will low sales such as South Dakota could be exammed to better improve order handling/delivery to various locations and encourage ordering.
