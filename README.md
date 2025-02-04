# PowerBI Sales dashboard Plant-Co. :rocket: :chart_with_upwards_trend:

## Overview
This is a practice project, but it has everything to show for to be a portfolio project. I wanted to demonstrate my powerbi skills but also give actual insights into the sales of a company uncovering insights under layers of data, which was made possible due to PowerBI's drill down feature, which is the reason i feel PowerBI's interface is the best for such a sales report deep dive. i utilized key metrics over different dimensions over a period of 3 years. this dashboard is designed to help stakeholders to track their strenghts and weaknesses interactively and aid in decision making. 

## Dataset
The dataset consists of three key tables:

Sales Data

* Product ID: Unique identifier for each product.

* Sales (USD): Revenue generated from product sales.

* Quantity Sold: Number of units sold.

* Price (USD): Selling price per unit.

* Cost of Goods Sold (USD): Direct cost associated with production.

* Transaction Date: Date of each sales transaction.

* Account ID: Unique identifier for customer accounts.

Account Information

* Country Code: Identifies the country associated with the account.

* Account Name: Name of the customer or business entity.

* Master Account ID: Parent account ID for related transactions.

* Latitude & Longitude: Geographic coordinates of the account.

* Country: Full name of the country.

* Postal Code: Postal region for customer location.

* Street Name & Number: Address details for customer segmentation.

Product Information

* Product Family: High-level categorization of products.

* Product Family ID: Unique identifier for product family.

* Product Group: More specific classification of products.

* Product Group ID: Unique identifier for product group.

* Product Name: Scientific or commercial product name.

* Product Name ID: Unique identifier for product name.

* Product Size: Size category (Small, Medium, Large).

* Product Type: Classification into Indoor, Landscape, or Outdoor categories.

## Key Metrics

Key Metrics involved were: 
* Sales 
* Quantity
* Gross Profit %: Calculated as (Sales - COGS) / Sales * 100, this metric indicates the profitability of sales.
* YTD (Year-to-Date) Measures: Sales, quantity, and gross profit measured from the start of the year.
* PYTD (Previous Year-to-Date) Measures: Sales, quantity, and gross profit measured for the same period in the previous year.
* YTD Vs PYTD Measures: Comapring sales, quantity, and gross profit from the start of the year against the same period last year.

## Dashboard Breakdown 

* Sales YTD vs PYTD | Month - Country - Product

A waterfall chart was utilized visualizing changes in sales, quantity, gross profit compared to last year.

Green bars represent an increase, red bars a decrease.

PowerBI's drill down feature can be used to follow the thought process - if a perticular month was low in sales since last year in which country did we see major decline and within that country which product struggled the most - this helps to get a picture of what sort of decrease is the company looking at down to bottom.

* Bottom 10 YTD vs PYTD | Country

A tree map highlighting countries with the largest sales decline.

* Sales YTD and PYTD | Month | Product Type

Monthly breakdown of sales by product category.

* Account Profitability Segmentation | GP% and Sales

Scatter plot with GP% on the Y-axis and sales on the X-axis.

## Insights 

## Installation & Setup

