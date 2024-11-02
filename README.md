# LITA-sales-Project
This project analyzes retail store sales data to reveal top products, regional performance, and sales trends. Using Excel, SQL, and Power BI, we explore metrics and create an interactive dashboard, enabling stakeholders to make data-driven decisions for sales optimization and strategic growth.
_______
## Project Title
Retail Sales Performance Analysis and Dashboard
_____
## Project Summary
In this project, the goal is to analyze the sales performance of a retail store, uncovering insights such as top-selling products, regional performance, and monthly sales trends. The objective is to produce an interactive Power BI dashboard that highlights these findings and provides a comprehensive view of sales performance for decision-making.
___
## Project Objectives
- Perform an initial data exploration in Excel to analyze sales by product, region, and month.
- Write SQL queries to extract key metrics, including total sales by category, regional sales, and top customer purchases.
- Visualize these insights in Power BI with an interactive dashboard that provides an accessible view of sales performance.
___
## Data Source
The dataset for this project was provided as part of a class assignment and contains simulated retail sales data for analysis purposes.
___
## Dataset
- The dataset used for this project contains the following fields:
- OrderID: Unique identifier for each order
- CustomerID: Identifier for each customer
- Product: Name of the product sold
- Region: Geographical region where the sale occurred
- OrderDate: Date the order was placed
- Quantity: Number of units sold
- UnitPrice: Price per unit of the product
- Revenue: Total revenue from each order (calculated as Quantity * UnitPrice)
____
 ## Tools used 
- Microsoft Excel:
  1. for data cleaning
  2. For analysis
- SQL- Structured Query Lnaguage for Data Querying
- Microsoft Power BI for data visualization
- Github for portfolio building
 ____
 ## Data Cleaning and Preparation
 ![Screenshot (17)](https://github.com/user-attachments/assets/e372917c-33a5-4a71-93b3-2d0d99f3024b)
 Before Cleaning
#### Remove Duplicates:
Highlighted all data (Ctrl + A) and removed duplicates via Data tab > Remove Duplicates option. This step removed 40,079 duplicate values, leaving 9,921 unique records. 
#### Reason:
Removing duplicates ensures data accuracy by eliminating repeated entries that could skew sales insights and lead to incorrect analysis.
#### Calculate Revenue:
Added a new column to calculate revenue using the formula Quantity * Unit Price for each order. 
#### Reason:
Calculating revenue allows us to analyze total earnings per product, region, and period, which is essential for evaluating sales performance and profitability.
![Screenshot (18)](https://github.com/user-attachments/assets/fdc9769b-7759-4378-8a86-380dcad956aa)
After Cleaning
______
## Instructions
1. Excel Data Exploration: Perform an initial exploration of the sales data. Use pivot tables to summarize 
- total sales by product, region, and month.
- Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.
- Create any other interesting report
2. SQL Data Analysis: Write queries to extract key insights based on the following questions. 
-retrieve the total sales for each product category.
- find the number of sales transactions in each region.
- find the highest-selling product by total sales value.
- calculate total revenue per product.
- calculate monthly sales totals for the current year.
- find the top 5 customers by total purchase amount.
- calculate the percentage of total sales contributed by each region.
- identify products with no sales in the last quarter.
3. Power BI: Create a dashboard that visualizes the insights found in Excel and SQL. The 
dashboard should include a sales overview, top-performing products, and 
regional breakdowns
___________
# Data Analysis
### Total Sales by Product
![Screenshot (20)](https://github.com/user-attachments/assets/3e64dc73-c39b-46f9-b047-6f674e213438)![Screenshot (27)](https://github.com/user-attachments/assets/1e81cc2c-b7df-4a05-9b61-a5b179bb3c6d)
Insight: Shoes and Shirts are the top-performing products in terms of revenue, indicating high customer demand or a potentially effective pricing strategy for these items. This insight can help guide inventory management and marketing focus on these best-selling products.
______
### Monthly Total Sales 
![Screenshot (28)](https://github.com/user-attachments/assets/5a8c56ac-e579-4785-8748-cbf7bacad07d)
![Screenshot (29)](https://github.com/user-attachments/assets/a1e1fd68-3c6f-4b32-90a7-2b1e7c653ade)
Insight: February shows the highest revenue, indicating strong sales during this month, potentially due to seasonal promotions or events. Conversely, September and December have the lowest revenues, suggesting the need for enhanced marketing strategies during these months to boost sales. Analyzing customer behavior and preferences during these periods may help in implementing effective sales tactics.
____
### Use Excel formulas to calculate metrics
#### Average Sales per Product 
Copy and paste the product to column K, then remove duplicate in order to have our unique product list. Then use the formular (AVERAGEIF($C:$C,K5,$H:$H)) to calculate our average sales for each product. Where “$C:$C” rep our product column, “K5” rep the product we are working with, “,$H:$H” rep our Sales Column.
![Average Sales by Product](https://github.com/user-attachments/assets/ee26db8d-a858-4f55-8dda-342e6a53b711)
![Screenshot (31)](https://github.com/user-attachments/assets/1faa8c40-f213-4298-bfcd-ac680966dc4f)

#### Total Revenue by Region.
Copy and paste the Region to column K, then remove duplicate in order to have our unique Region list. Then use the formular (SUMIF(D:D,K15,H:H)) to calculate our sum of revenue for each region. Where “D:D” rep our Region column, “K15” rep the region we are working with, “,H:H” rep our Revenue Column.
![Screenshot (30)](https://github.com/user-attachments/assets/9f5280c2-a87d-40a2-abb0-a741e6a55ef2)
![Screenshot (26)](https://github.com/user-attachments/assets/c5f47410-9723-4a39-9bf2-404fe59ee43d)
Insight: The South region leads in total revenue, suggesting either a larger customer base, higher demand, or possibly more effective sales strategies in this area. Focusing marketing and inventory efforts in the South region could further boost overall sales. Additionally, examining why the West region has the lowest revenue may reveal opportunities for improvement or targeted sales strategies.
#### Create any other interesting report

Insight:
- Regional Performance: The North region shows significant investment in Jackets and Shirts, indicating popularity or potential price increases in these categories. The South region has high unit prices for Shoes, suggesting either higher demand or premium pricing strategies.
- Opportunities for Growth: Gloves and Hats have lower total unit prices in some regions, indicating potential for targeted promotions or marketing to enhance sales in those areas.
#### 
#### 
####
####
####
####
####
####
####
####
####
##
####
##
##
########
##
##
####
