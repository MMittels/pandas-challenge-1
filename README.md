# Pandas Challenge 1
## Overview
A dataset from a fictional e-commerce company is explored and analyzed to address real-world business questions.

## Description
This project consists of three steps used to understand the fictional e-commerce company data. The first is to read in and explore the data by identifying popular products and top customers. The second step is to transform the data, which involves adding columns to calculate profits. The third step is to summarize and analyze the data around the top five clients in the data.

## Explore the Data
In order to start the analysis, client_dataset.csv is read in and explored by looking at the columns (df.columns), summary statistics (df.describe), and underestand the length and width of the dataset (df.shape). Then digging into the dataset the top category and subcategories are identified, along with the top five clients based on frequency in the dataset. 

## Transform the Data
To ultimately understand the profit gained through each order and client a few columns are created:
-  line_subtotal = qty * unit_price
-  shipping_price = total weight * 7 (or 10 depending on weight)
-  line_price = adding sales tax (9.25%) to line_subtotal and shipping_price
-  line_cost = shipping_price + (unit_cost * qty) 
-  line_profit = line_price - line_cost

## Confirm your Work
Three receipts were provided and code was written to validate data matches the receipts.

## Summarize and Analyze