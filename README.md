# Target E-Commerce SQL Case Study

# Project Overview:
Target is one of the largest retail companies in the world, known for delivering exceptional customer experiences and value-driven shopping.
In this case study, I analyzed Target's Brazil e-commerce operations using transactional data containing approximately 100,000 orders placed between 2016 and 2018.
The objective of this project was to explore customer purchasing behavior, order trends, payment patterns, logistics performance, and delivery efficiency to derive actionable business insights and recommendations.

# Business Problem

As a Data Analyst at Target, the goal is to understand:

How customer orders evolved over time.
Customer distribution across Brazilian states.
Payment preferences and installment usage.
Revenue and freight trends.
Delivery performance and logistics efficiency.
Areas where business operations can be optimized.

# Dataset Information
Dataset: https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb

The data is available in 8 csv files:

customers.csv
sellers.csv
order_items.csv
geolocation.csv
payments.csv
reviews.csv
orders.csv
products.csv

FeatureDescriptioncustomer_idID of the consumer who made the purchasecustomer_unique_idUnique ID of the consumercustomer_zip_code_prefixZip Code of consumer’s locationcustomer_cityName of the City from where order is madecustomer_stateState Code from where order is made (Eg. são paulo - SP)

Time Period Covered
September 2016 – October 2018

Total Orders Analyzed
~100,000 Orders

# Entity Relationship Overview

The analysis was performed by joining multiple tables using primary and foreign keys:

customers ↔ orders
orders ↔ order_items
orders ↔ payments
orders ↔ reviews
order_items ↔ products
order_items ↔ sellers

# SQL Concepts Used

This project demonstrates the use of:

SELECT Statements
Aggregate Functions
GROUP BY & HAVING
CASE Statements
Common Table Expressions (CTEs)
Joins
Date Functions
Window Functions
Subqueries
