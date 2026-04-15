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
- What are the overall sales over time?
- Which drinks provide the highest and lowest sales?
- Which drinks are the most and least ordered?
- What are the rush hour periods throughout the day?
- Are there seasonal changes in customers’ ordering behavior?

### 7. Analysis 
- Analyzed monthly sales trends to identify growth and decline periods
- Compared different drinks based on sales contribution and quantity sold.
- Explored seasonal variations in ordering behavior.

### 8. Visualization 
#### [Dashboard One: Coffee Sales](https://github.com/noura-tarek-m/coffee-sales-analysis/blob/main/project-images/Screenshot%202026-02-20%20232703.png)
This dashboard aims to analyze sales trend over time, sales and orders contribution of different drinks, and order frequency changes throughout the day. It contains the following KPIs: total sales, orders, and average order value. It visualizes sales trends over time, orders by daytime, drinks contribution to sales and orders, and compares yearly sales. It helps in determining highly demanded drinks, rush hours, and seasonal sales peaks.
 
### 9. Key Findings (Insights) & Recommendations 
1.	The sales achieved in 2025 are much less than 2024, but we are only through the first quarter of 2025, thus there is no point of comparison in the meantime.
2.	Orders and sales increase throughout February, March, Sep, Oct, and Nov (1st and 4th quarters of the year, specifically). 
3.	More orders come in the late morning (11 AM) and afternoon period (4 PM). The café must make sure of staff and drinks availability throughout these periods urgently.
4.	Generally, demand slightly decreases at nighttime. Accordingly, perishable ingredients redundancy should be adjusted to avoid ingredient wastage. 
5.	Latte and americano with milk are the drinks with highest sales, while cortado and espresso had the least sales. Some drinks, especially caffeinated ones such as americano and americano with milk are mostly demanded in the morning. On the other hand, soothing drinks such as hot chocolate, cocoa, and cappuccino are mostly ordered during the night. Ingredients redundancy should be adjusted accordingly.
