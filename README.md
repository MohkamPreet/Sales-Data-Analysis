# Project Title: Analyzing E-commerce Transactions for Enhanced Customer Insights and Business Optimization

This is a Group project for Big data Visulization for business and communication.

Group members for this Project are:

1. Ronakkumar Chavda 
2. Rahul Rawat 
3. Mohkampreet Kaur

## Table of Contents
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Data Splitting](#data-splitting)
- [Regression Analysis](#regression-analysis)

## Introduction
In today’s fast-paced e-commerce landscape, grasping customer behavior and streamlining business operations are essential for thriving. This project intends to explore an extensive dataset of e-commerce transactions to uncover meaningful insights and support strategic decision-making. The dataset encompasses a range of details, including transaction specifics, customer demographics, purchasing patterns, and product information.

## Dataset Description
The dataset includes the following attributes:

- Transaction Details: Transaction_ID, Date, Year, Month, Time, Total_Purchases, Amount, Total_Amount.
- Customer Information: Customer_ID, Name, Email, Phone, Address, City, State, Zipcode, Country, Age, Gender, Income, Customer_Segment.
- Product Information: Product_Category, Product_Brand, Product_Type, products.
- Feedback and Logistics: Feedback, Shipping_Method, Payment_Method, Order_Status, Ratings.

## Data Cleaning and Preprocessing
This process includes:
- Identification and handling of missing values
- Correction of errors and inconsistencies
- Detection and handling of outliers
- Ensuring correct data types and consistent formatting

## Feature Engineering
This process includes:
- Create new features based on the existing ones.
- Encode categorical variables using techniques like one-hot encoding or label encoding.
- Scale numerical features using standard scaling (StandardScaler in Python).

## Data Splitting
This process includes:
- Split the data into training and testing sets using a 80/20 split.
- Use a random state of 0 to ensure reproducibility.

## Regression Analysis
This process includes:
- Perform Linear Regression, Lasso Regression, Ridge Regression, and Elastic Net Regression on the dataset.
- Evaluate and compare the performance of these models using r2_score, mae, mse, and rmse metrics.