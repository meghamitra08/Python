# Diwali_Sales_Analysis using Python
This Python project is to analyze Diwali sales data to improve customer experience and sales.

Key Objective:
The objective of this analysis is to explore the Diwali sales data, identify key patterns, and understand customer purchasing behavior based on various demographic and product-related attributes. The analysis focuses on customer segmentation, sales distribution across different regions, product categories, and the relationship between various factors such as age, marital status, occupation, and sales performance.

Techniques Used:
Data Cleaning & Preprocessing:

Importing necessary Python libraries (pandas, numpy, matplotlib, seaborn).
Reading CSV file and exploring the dataset structure.
Handling missing values and ensuring proper data types (e.g., changing the 'Amount' column to integer).
Dropping irrelevant columns.
Descriptive Statistics:

Using the describe() function to summarize key numerical data and understand data distributions (e.g., mean, min, max, etc.).
Data Visualization:

Countplots: Visualizing the frequency distribution of categories like Gender, Age Group, Marital Status, Occupation, and Product Category.
Barplots: Visualizing the total sales and number of orders for different categories (e.g., sales by Gender, Age Group, State, Occupation, Product Category).
Grouping data using groupby() and calculating aggregated values such as total sales (Amount) and total orders.
Exploratory Data Analysis (EDA):

Analyzing sales trends based on customer demographics, including gender, age group, marital status, occupation, and product category.
Identifying top-selling products and regions (states) contributing to high sales.
Key Factors Analyzed:
Gender: Analyzed the purchasing behavior based on gender, revealing that females are the primary purchasers and have higher purchasing power than males.

Age Group: The age group 26-35 years, especially females, contributes the most to sales.

State: Uttar Pradesh, Maharashtra, and Karnataka are the top states for both the number of orders and total sales.

Marital Status: Married individuals, particularly married women, exhibit higher purchasing power.

Occupation: The most significant purchasing groups come from sectors such as IT, Healthcare, and Aviation.

Product Category: Products in the Food, Clothing, and Electronics categories are the most sold.
