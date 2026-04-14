# **Superstore Sales Analysis** 
![Superstore icon](https://cdn-icons-png.flaticon.com/512/8422/8422894.png)
### >> Objective
----------------
This project aims to analyze superstore sales and customer transaction data over the span of 5years (2014, 2015, 2016, 2017, 2018) in order to drive insights regarding high-demand products, regions with most demanding customers, and determine how to further increase sales and prevent decline, while maintaining customer base and increasing repeating customers.

### >> Data Cleaning
----------------
1.	Removed “Row ID” and “Postal Code” columns.
2.	Renamed “Sales” column to “SalesAfterDiscount”
3.	Added “SalesB4Discount” column = “Sales” /(1- “Discount”)
4.	Added “Cost” column = “Sales” – “Profit”
5.	Added “Unit Price” = ”SalesB4Discount”/”Quantity”
6.	Added “Unit Cost” = “Cost” / “Quantity”
7.	Changed columns data types to suitable data types.
8.	Trimmed text columns
9.	Created “DimCustomers” table with the following referenced columns: Customer ID, Customer Name, Segment, Country, City, State, Region.
10.	Created “DimProducts” table with the following referenced columns: Product ID, Category, Sub-Category, Product Name, Unit Price, Unit Cost
11.	Created “FactOrders” table with the following referenced columns: Order ID, Order Date, Ship Date, Ship Mode, Quantity, SalesB4Discount, Discount, SalesAfterDiscount, Cost, Profit.
12.	Removed duplicate data from “Customers” and “Products” tables.
13.	Add “DimDate” table with the following columns: Full Date, Year, Quarter, Month, Month Name, Day, Day Name.

### >> Questions to Answer
----------------
-	What is our achieved sales and sold quantity?
-	What big is our customer base?
-	What is the ratio of returning customers compared to total customers?
-	What is the total number of completed orders?
-	What is the average order value?
-	What is our achieved profit margin compared to sales?
-	Which year had the best/worst sales
-	Which months are of highest demand?
-	Which region/country had the least orders and sales?
-	Wihch product category/sub-category achieved the highest sales?
-	which product category/sub-category had the most demands?
-	Which shipmode provided highest sales?

-	>>average discount of each category/sub category<<

### >> Data Visualization
----------------
#### Dashboard One: Sales Analysis
**KPIs**
-	Total Sales
-	AOV Sales
-	AOV Quantity
-	Total Orders
-	Total Quantity

**Charts**
-	Sales and quantity over months
-	Sales and quantity over years
-	Sales and orders based on shipping mode
-	Cost vs sales vs profit (profit margin %)

**Slicers**
Year, quarter, month, day, shipping mode slicers

#### Dashboard Two: Product Analysis
**KPIs**
-	Total Categories
-	Total Sub categories
-	Total Products
-	
**Charts**
Sales share (%) of categories
Sales and quantity based on category (drill throughsub-category)
Products table? (hierarchical)  to find most demand

**Slicers**
Category, sub-category, product

#### Dashboard Three: Customer Analysis
**KPIs**
-	Total Customers
-	Total Repeating Customers
-	Customers Return Rate
-	
**Charts**
-	Sales share over segments
-	Orders/sales over Regions
-	Geographical visualization of sales share over region/country/state/city

**Slicers**
-	Region, state, city

### >> Findings and Insights
----------------
