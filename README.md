# LITA-sales-Capstone-Project
This project analyzes retail store sales data to reveal top products, regional performance, and sales trends. Using Excel, SQL, and Power BI, we explore metrics and create an interactive dashboard, enabling stakeholders to make data-driven decisions for sales optimization and strategic growth.
_______
## Project Title
Retail Sales Performance Analysis and Dashboard
_____
## Outline
[Project Summary](#project-summary)

[Project Objectives](#project-objectives)

[Data Source](#data-source)

[Dataset](#dataset)

[Tools used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Instructions](#instructions)

[Data Analysis](#data-analysis)
- [Excel](#excel)
- [SQL](#sql)

  [Key Findings](#key-findings)

  [Conclusion](#conclusion)

  [Recommendation](#recommendation)
_______
## Project Summary
In this project, the goal is to analyze the sales performance of a retail store, uncovering insights such as top-selling products, regional performance, and monthly sales trends. The objective is to produce an interactive Power BI dashboard that highlights these findings and provides a comprehensive view of sales performance for decision-making.
![Screenshot (55)](https://github.com/user-attachments/assets/79e1b9ee-2fc8-45e4-ae85-6c4094136dd8)
______
## Project Objectives
- Perform an initial data exploration in Excel to analyze sales by product, region, and month.
- Write SQL queries to extract key metrics, including total sales by category, regional sales, and top customer purchases.
- Visualize these insights in Power BI with an interactive dashboard that provides an accessible view of sales performance.
________
## Data Source
The dataset for this project was provided as part of a class assignment and contains simulated retail sales data for analysis purposes.
________
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
_______
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
____
## Excel
#### Total Sales by Product
![Screenshot (57)](https://github.com/user-attachments/assets/64a31b5d-501a-40b2-99c4-88389f10bb1d)
![Screenshot (27)](https://github.com/user-attachments/assets/1e81cc2c-b7df-4a05-9b61-a5b179bb3c6d)
Insight: Shoes and Shirts are the top-performing products in terms of revenue, indicating high customer demand or a potentially effective pricing strategy for these items. This insight can help guide inventory management and marketing focus on these best-selling products.
______
#### Monthly Total Sales 
![Screenshot (58)](https://github.com/user-attachments/assets/bd76bb49-2997-4bb3-a152-3c9166baec77)
![Screenshot (29)](https://github.com/user-attachments/assets/a1e1fd68-3c6f-4b32-90a7-2b1e7c653ade)
Insight: February shows the highest revenue, indicating strong sales during this month, potentially due to seasonal promotions or events. Conversely, September and December have the lowest revenues, suggesting the need for enhanced marketing strategies during these months to boost sales. Analyzing customer behavior and preferences during these periods may help in implementing effective sales tactics.
____
### Use Excel formulas to calculate metrics
#### Average Sales per Product 
Copy and paste the product to column K, then remove duplicate in order to have our unique product list. Then use the formular (AVERAGEIF($C:$C,K5,$H:$H)) to calculate our average sales for each product. Where “$C:$C” rep our product column, “K5” rep the product we are working with, “,$H:$H” rep our Sales Column.
![Screenshot (61)](https://github.com/user-attachments/assets/ac4a6688-ec9a-47a0-88be-8a5e1c3da15b)
![Screenshot (31)](https://github.com/user-attachments/assets/1faa8c40-f213-4298-bfcd-ac680966dc4f)
_____
#### Total Revenue by Region.
Copy and paste the Region to column K, then remove duplicate in order to have our unique Region list. Then use the formular (SUMIF(D:D,K15,H:H)) to calculate our sum of revenue for each region. Where “D:D” rep our Region column, “K15” rep the region we are working with, “,H:H” rep our Revenue Column.
![Screenshot (62)](https://github.com/user-attachments/assets/4bf50923-128e-4ad7-a052-173762fe0104)
![Screenshot (26)](https://github.com/user-attachments/assets/c5f47410-9723-4a39-9bf2-404fe59ee43d)
Insight: The South region leads in total revenue, suggesting either a larger customer base, higher demand, or possibly more effective sales strategies in this area. Focusing marketing and inventory efforts in the South region could further boost overall sales. Additionally, examining why the West region has the lowest revenue may reveal opportunities for improvement or targeted sales strategies.
_______
#### Create any other interesting report
![Screenshot (60)](https://github.com/user-attachments/assets/d7a2fabd-61d4-4a1f-a203-bb1a959337fe)
![Screenshot (32)](https://github.com/user-attachments/assets/2f39d395-a400-4465-9083-34bfdee5ede3)
Insight:
- Regional Performance: The North region shows significant investment in Jackets and Shirts, indicating popularity or potential price increases in these categories. The South region has high unit prices for Shoes, suggesting either higher demand or premium pricing strategies.
- Opportunities for Growth: Gloves and Hats have lower total unit prices in some regions, indicating potential for targeted promotions or marketing to enhance sales in those areas.
  ______
## SQL
When loading my dataset I changed the unitsales and quantity column to “int” datatype

#### ADDED A COLUMN NAME SALES
```SQL
Alter Table [dbo].[LITA Capstone Dataset SalesData]
add Sales int
```
![Screenshot (37)](https://github.com/user-attachments/assets/fdb8d1ed-7bde-4131-bbec-d89948d0fb0a)

________
#### SALES COLUMN WAS CALCULATED
```SQL
(Update [dbo].[LITA Capstone Dataset SalesData]
Set Sales = quantity * unitprice)
```
![Screenshot (38)](https://github.com/user-attachments/assets/39604984-88e4-482c-994d-d9516f1d7e08)

_______
#### retrieve the total sales for each product category.
```SQL
select Product,
Count (OrderId) as Total_sales
from [dbo].[LITA Capstone Dataset SalesData]
group by Product
Order by Total_sales desc
```
![Screenshot (56)](https://github.com/user-attachments/assets/3f5d459f-8c58-42f6-94ea-b759803ee927)
______![Screenshot (53)](https://github.com/user-attachments/assets/e2c735da-d1d9-4fcf-907d-6348b04257ee)
Insight: Hats and Shoes are the top-ordered products, suggesting strong customer demand for these items. Focusing on promotions and inventory for these products could maximize revenue. Conversely, Gloves and Socks have the lowest order counts, indicating potential areas for targeted marketing or bundled sales strategies to boost demand.
______
#### find the number of sales transactions in each region.
```SQL
select Region,
Count (OrderID) as NumberofSalesTransaction
from [dbo].[LITA Capstone Dataset SalesData]
group by Region
```
![Screenshot (40)](https://github.com/user-attachments/assets/b2db43d6-e58c-42b9-91c2-622b87b4b954)
![Screenshot (50)](https://github.com/user-attachments/assets/31e9b64e-0be5-4d20-95c0-006207792b6a)
________
#### find the highest-selling product by total sales value.
```SQL
select top 1 Product,
sum (sales) AS Total_sales
from [dbo].[LITA Capstone Dataset SalesData]
group by product
order by Total_sales desc
```
![Screenshot (41)](https://github.com/user-attachments/assets/043dedba-ba36-445e-833c-2673019e56d4)
![Screenshot (51)](https://github.com/user-attachments/assets/f45145c1-085f-4833-8d8d-16a100100172)
________
#### calculate total revenue per product.
```SQL
select top 1 Product,
sum (sales) AS Total_sales
from [dbo].[LITA Capstone Dataset SalesData]
group by product
order by Total_sales desc
```
![Screenshot (43)](https://github.com/user-attachments/assets/a8e31822-eb18-4015-80dc-1df32ae6e26a)
![Screenshot (49)](https://github.com/user-attachments/assets/59e5bc30-e6a8-46cc-848a-4c2be46e4b9c)
_________
#### calculate monthly sales totals for the current year.
```SQL
select month (OrderDate) as Sales_month,
sum (Sales) As Total_sales
from [dbo].[LITA Capstone Dataset SalesData]
Where year(OrderDate) =year (getdate())
group by month (OrderDate)
Order by Sales_month
```
![Screenshot (44)](https://github.com/user-attachments/assets/76d7de1a-cff3-4fdd-abc5-dabce3dd3a2e)
_______
#### find the top 5 customers by total purchase amount.
```SQL
select top 5 Customer_Id,
sum (Sales) as Total_sales
from [dbo].[LITA Capstone Dataset SalesData]
group by Customer_Id
order by Total_sales desc
```
![Screenshot (46)](https://github.com/user-attachments/assets/95b75503-1c7e-49a8-a580-fc27198df352)
_______
#### calculate the percentage of total sales contributed by each region.
```SQL
select Region,
sum (Sales) as Total_sales,
(sum (sales)*100/
(select sum (sales) from [dbo].[LITA Capstone Dataset SalesData])) as Sales_percentage
from [dbo].[LITA Capstone Dataset SalesData]
group by Region
order by Sales_percentage DESC
```
![Screenshot (47)](https://github.com/user-attachments/assets/1c2ab858-4a0c-4fb0-9416-ff3cadc94712)
![Screenshot (54)](https://github.com/user-attachments/assets/5df8a24b-3718-4904-879a-9a57c9ce10fe)
______
#### identify products with no sales in the last quarter.
```SQL
SELECT DISTINCT Product 
FROM [dbo].[LITA Capstone Dataset SalesData]
WHERE Product NOT IN 
(SELECT Product
FROM [dbo].[LITA Capstone Dataset SalesData]
WHERE OrderDate >= DATEADD(QUARTER, -1, GETDATE()))
```
![Screenshot (48)](https://github.com/user-attachments/assets/13e9bb14-ed50-460e-8cda-ad1ee4a38cb3)
_______
### Key Findings
- Highest Selling Product:
Shoes generated the highest revenue, totaling 613,380 units sold.
- Revenue by Region:
The South region was the top-performing region, generating 927,820 in revenue, followed by East and North regions.
- Sales Trends by Month:
Sales peaked in February with a revenue of 546,300, while the lowest sales occurred in September and October, indicating a seasonal sales dip.
- Customer Insights:
After removing duplicates, we retained 33,787 unique customer entries, indicating a substantial customer base that could be better segmented for targeted marketing.
________
### Conclusion
The analysis reveals a few key insights:
- Product Performance: Shoes are the most popular item, representing a high sales value across all regions. However, products like Socks and Jackets are lower performers, suggesting potential for improved marketing or bundling strategies.
- Regional Sales: The South region shows a significantly higher revenue contribution, which could indicate a strong customer preference or effective marketing strategies within this region.
- Seasonal Sales Patterns: Sales exhibit a spike early in the year (February) and a drop in late summer and early fall (September-October). This could be due to seasonality or external factors impacting consumer spending.
  _________
### Recommendation
- Enhance Marketing for Top-Performing Products
Focus on marketing campaigns that promote the top-selling product categories, especially Shoes. Highlighting their popularity could increase brand trust and encourage further purchases.

- Product Diversification and Bundling Opportunities
To boost revenue from low-performing items like Socks and Jackets, consider creating product bundles or seasonal discounts. This could attract budget-conscious customers and increase average sales per customer.

- Targeted Regional Campaigns
With the South region demonstrating the highest revenue, additional promotional efforts in East and West could help balance sales distribution. A focus on localized marketing strategies may appeal to unique preferences in each region.

- Address Seasonal Sales Fluctuations
To combat the dip in sales observed in September and October, consider introducing seasonal promotions or limited-time offers during these months to stimulate demand.

- Customer Segmentation and Retention
With a large unique customer base, implementing customer segmentation could allow for more tailored marketing. Sending targeted offers based on past purchases can help drive repeat sales and improve customer loyalty.
