# Home_Sales

### Home Sales Data Analysis


This repo contains codes for analyzing home sales data using Apache Spark. The code demonstrates various Spark operations, including reading data from AWS S3, caching data, partitioning Parquet data, and running queries for filtering and aggregating data. The goal is to provide insights into the average prices of homes based on different criteria such as bedrooms, bathrooms, floors, square footage, and year built.

### Necessary steps to analyze the home_sales data

1.Read the home sales data from an AWS S3 bucket into a Spark DataFrame.
2.Cache the DataFrame or temporary table to improve query performance.
3.Partition the formatted Parquet data by specific columns, such as date built.
4.Run queries on the cached data to filter and aggregate information.
5.Compare the runtime performance between using the cached data and working with Parquet data directly.


The analysis of the home sales data allows for various insights into housing trends. By filtering the data based on criteria such as bedrooms, bathrooms, floors, square footage, and year built, we can identify patterns and trends in home prices.
The average price calculations provide a summary measure to understand the overall pricing trends. By rounding the average prices to two decimal places, we obtain a clearer view of the pricing patterns. Additionally, categorizing the average prices into "High" and "Low" view ratings based on a threshold, such as $350,000, allows for further segmentation and analysis.








