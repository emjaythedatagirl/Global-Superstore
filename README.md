# Global-Superstore

![](superstore.PNG)

## Project Overview

This project analyzes sales performance, profitability, and operational efficiency of a Global Superstore using Microsoft Excel.
The goal is to uncover business insights that can guide decision-making around markets, products, pricing, discounts, and shipping operations.

## Business Objectives

The analysis was guided by the following objectives:

- Understand overall sales and profit performance across markets

- Identify profitable and loss-making regions, categories, and products

- Evaluate the impact of discounts on profitability

- Analyze shipping efficiency and its relationship with profit

- Provide actionable insights through dashboards and visual storytelling

 ## Dataset Description

**Source*: Kaggle – Global Superstore Dataset
*Scope*: Global sales transactions across multiple regions and years

**Key Columns Used**

**Time**: Order Date, Ship Date, Year, Week Number

**Geography**: Market, Region, Country, State, City

**Product**: Category, Sub-Category, Product Name

**Customer**: Segment, Customer ID

**Sales Metrics**: Sales, Profit, Quantity, Discount

**Operations**: Ship Mode, Shipping Cost, Order Priority

Note: The Discount column is binary (0 = no discount, 1 = discount applied).


## Tools & Techniques

*Microsoft Excel*

- Power Query (data cleaning & transformation)

- Power Pivot (data modeling)

- DAX measures (KPIs)

- Pivot Tables & Pivot Charts

- Excel Dashboards
  

## Key Metrics (KPIs)

The following KPIs were created using DAX:

Total Revenue: 

Total Profit

Profit Margin

Average Profit

Shipping Duration (Ship Date − Order Date)

Key Business Questions Answered
1️⃣ Overall Performance

What is the total revenue, total profit, and profit margin of the Global Superstore?

✔ Identified overall business profitability and baseline performance.

2️⃣ Market & Regional Performance

Which markets and regions generate the highest and lowest revenue and profit?

✔ APAC, EU, and US drive the largest revenue
✔ Some regions generate high sales but relatively low profit margins

3️⃣ Product Category Performance

Which product categories and sub-categories are the most and least profitable?

✔ Technology is the most profitable category
✔ Furniture shows weaker margins in several regions

4️⃣ Loss-Making Products

Which products consistently generate losses despite high revenue?

✔ Identified top 10 loss-making products
✔ Several high-revenue products contribute negatively to profit

5️⃣ Discount Impact Analysis

How do discounts affect profit and revenue?

✔ Discounted orders generate revenue but significantly reduce profit
✔ Non-discounted orders are consistently more profitable

6️⃣ Time-Series Performance

How do sales and profit trend over time (yearly)?

✔ Sales are relatively stable across years
✔ Profitability varies by year, indicating efficiency and cost challenges

7️⃣ Shipping Efficiency

How long does it take to ship orders, and does shipping delay affect profit?

✔ Shipping duration was calculated using Order Date and Ship Date
✔ Faster ship modes tend to be more profitable
✔ Longer shipping times are associated with reduced profit
