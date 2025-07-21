# ACCESSORIES-ANALYSIS
## Table of Contents
+ [Project Overview](#Project-Overview)
+ [Dataset Description](#Dataset-Description)
+ [Objectives](#Objectives)
+ [Tools Used](#Tools-Used)
+ [Analysis and Insight](#Analysis-and-Insight)
+ [Pivot Table](#Pivot-Table)
+ [Excel Dashboard](#excel-dashboard)
+ [SQL Queries](#sql-queries)
+ [Power Bi Dashboard](#Power-Bi-Dashboard)
+ [Findings](#Findings)
---
## Project Overview
#### This Project analyses a sales record that documents transactions performed by various consumers over time, specifically for bike rack accessories (Hitch Rack).  With information on the client, the goods, and financial KPIs, each row in the dataset represents a separate sales order.
---

## Data Description
| **Column**           | **Description**                                                       |
| -------------------- | --------------------------------------------------------------------- |
| `Date`               | Date the sales transaction occurred.                                  |
| `Customer ID`        | Unique identifier for each customer.                                  |
| `Customer Age Group` | Age and gender classification (e.g., Youth (<25) M, Adults (35) F).   |
| `Customer Country`   | Country of the customer (e.g., Canada, Australia).                    |
| `State`              | Customer's state or province.                                         |
| `Product Category`   | Product category (in this case, all are *Accessories*).               |
| `Sub Category`       | Sub-category of the product (*Bike Racks*).                           |
| `Product`            | Specific product type (*Hitch Rack*).                                 |
| `Frame Size`         | Frame size (value appears to be 0 throughout, may not be applicable). |
| `Order Quantity`     | Number of items ordered.                                              |
| `Unit Cost`          | Cost to produce or purchase one unit of the item.                     |
| `Unit Price`         | Price charged per unit sold.                                          |
| `Cost`               | Total cost for the order (Unit Cost × Quantity).                      |
| `Revenue`            | Total revenue from the sale (Unit Price × Quantity).                  |
| `Profit`             | Profit from the order (Revenue − Cost).                               |

---
## Objectives
+ To comprehend seasonality or long-term growth, find trends in sales volume, revenue, and profit over several months or years.
+ To assist with focused marketing, investigate how age and gender affect order quantity, profitability, and purchasing behavior.
+ To determine high-performing regions and places that require work, compare sales performance across states and nations (for example, Australia vs. Canada).
+ To Find out which client or geographic areas produce the largest profit margins and which may be causing losses.
+ To inform more sensible pricing and discounting practices, assess the impact of unit price against unit cost on total profit per order.
---
## Tools Used
+ MICROSOFT EXCEL
+ POWER BI
+ SQL
---
# Analysis and Insight 
##  Excel Dashboard
#### https://ibb.co/7t7t5QbM

##  SQL Queries
#### https://ibb.co/20wfwMGL
#### https://ibb.co/BHd1qn1B

##  Power Bi Dashboard
#### https://ibb.co/zTPXDVGr
#### https://ibb.co/g2hsHt3
---
# Findings
### 1. Most Orders Are Shipped:
   The majority of the orders in the dataset have a status of "Shipped", indicating a high fulfillment rate and good operational flow.
### 2. Popular Product Line – Motorcycles:
   All visible entries are from the Motorcycle product line, suggesting that this product category may be a major revenue driver.
### 3. Order Volumes Vary:
   The quantity ordered ranges from small (e.g., 1 unit) to larger bulk orders (up to 66 units), indicating a mix of retail and possible wholesale transactions.
### 4. Sales Values Differ Widely:
   The sales amounts (total revenue per order line) vary significantly, showing different pricing tiers and customer spending levels.
### 5. Geographically Diverse Customers:
   Customers are located in various countries including the **USA, France, Australia, UK, Norway, and Spain**, highlighting an international customer base.
### 6. Active Customer Engagement:
   Each record contains full contact information (phone, address, and names), suggesting that the company maintains detailed CRM (Customer Relationship Management) records.
### 7. Recent Sales Activity:
   Many order dates fall in 2020, showing relatively recent business activity and suggesting the data is used for current performance monitoring.




