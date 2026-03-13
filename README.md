# 📱 Mobile Store Sales Analysis Dashboard – Power BI Project
An interactive Power BI dashboard that analyzes mobile store sales data to uncover insights about sales performance, product trends, customer behavior, and payment methods.

This project demonstrates data cleaning, transformation, DAX calculations, and interactive visualization skills for real-world data analytics scenarios.

## Project Overview

Retail businesses generate large amounts of sales data daily. Analyzing this data can help businesses understand:

* Which mobile brands sell the most
* Which products generate the highest revenue
* How customers prefer to pay
* Sales patterns across time and location

Here Power BI dashboard transforms raw transactional data into actionable insights for business decision making.

## Project Objectives

* Analyze total sales and revenue
* Identify top selling brands and models
* Understand customer demographics and behavior
* Analyze payment methods used by customers
* Track sales performance over time
* Evaluate customer satisfaction through ratings

##  Tools & Technologies Used
* Power BI	Data visualization & dashboard
* Power Query	Data cleaning & transformation
* DAX	Calculated measures
* Excel	Data source
* GitHub	Project version control

## Dataset Description

The dataset contains mobile sales transactions with the following information:

| Column | Description |
|------|-------------|
| Transaction ID | Unique identifier for each sale |
| Date | Sales transaction date |
| Day Name | Day of the week |
| Brand | Mobile phone brand |
| Mobile Model | Phone model sold |
| Units Sold | Quantity sold |
| Price Per Unit | Price of each phone |
| Customer Name | Buyer information |
| Customer Age | Customer demographic data |
| City | Location of the customer |
| Payment Method | Payment mode used |
| Customer Ratings | Customer satisfaction rating |


 ## Key Dashboard Features
### Sales Overview
* Total Revenue
* Total Units Sold
* Total Transactions

### Brand Performance
* Sales comparison by mobile brand
* Identification of top selling brands

### Product Analysis
* Best selling mobile models
* Revenue contribution by product

### Customer Insights
* Sales distribution by city
* Age group analysis

### Payment Analysis
* Cash vs Digital payments
* Payment method trends

### Customer Satisfaction
* Customer rating analysis
* Product satisfaction insights

### DAX Measures Used
* Total Revenue

Total Revenue =SUMX(
    'Mobile Sales Data',
    'Mobile Sales Data'[Units Sold] *
    'Mobile Sales Data'[Price Per Unit]
)
* Total Units Sold

Total Units Sold = SUM('Mobile Sales Data'[Units Sold])
* Average Customer Rating

Average Rating = AVERAGE('Mobile Sales Data'[Customer Ratings])

### Data Preparation Process

* Imported dataset into Power BI
* Cleaned data using Power Query
* Verified data types and handled inconsistencies
* Created calculated columns and DAX measures
* Built an optimized data model
* Designed interactive visuals and slicers

## Dashboard Preview



## Key Insights

* Some mobile brands dominate total sales revenue.
* Digital payment methods such as UPI and credit cards are widely used.
* Higher customer ratings indicate popular mobile models.
* Sales patterns vary across different cities.
* Certain models generate significantly higher revenue.

##  Business Impact
### This dashboard helps store managers to:
* Monitor real-time sales performance
* Improve inventory management
* Identify high demand products
* Understand customer buying behavior
* Make data-driven decisions



### Author

Reshma Das Mohapatra

Data Analyst | Power BI | SQL | Excel | Python
