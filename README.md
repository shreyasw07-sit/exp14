
Data Binning and Formatting with Python (Pandas & NumPy)
Project Overview
This repository contains a comprehensive Python implementation of Data Binning and Data Formatting techniques using the pandas and numpy libraries. The code demonstrates how to transform raw numerical data into structured categorical groups and how to standardize data types and string formats for better readability and analytical readiness.

Core Objectives
Data Binning: Transforming continuous numerical variables into discrete categories (bins) to simplify analysis and identify patterns.

Data Formatting: Standardizing data types, adjusting string casing, and rounding values to ensure consistency across the dataset.

Data Manipulation: Sorting and calculating frequency distributions of categorized data.

Technical Stack
Language: Python

Libraries: * pandas: Used for DataFrame creation, binning via pd.cut(), and data type casting.

numpy: Supporting numerical operations.

Environment: Jupyter Notebook / Google Colab

Detailed Implementation Breakdown
1. Electronics Product Dataset
The first part of the experiment focuses on a retail scenario involving product pricing and sales volume.

Initialization: Creates a DataFrame with Product, Price, and Units_Sold.

Price Binning: Groups prices into Low, Medium, and High categories using defined thresholds:

0−10,000: Low

10,001−30,000: Medium

30,001−60,000: High

Sales Binning: Categorizes Units_Sold into Low Sales, Medium Sales, and High Sales.

Formatting Operations:

Type Casting: Converts Units_Sold from integer to float.

String Normalization: Converts product names to uppercase (e.g., "Laptop" → "LAPTOP").

Rounding: Ensures prices are rounded to two decimal places.

Sorting: Demonstrates both ascending and descending sorts based on the Price column.

2. Food Delivery Orders Dataset
The second part applies similar logic to a logistics dataset to categorize delivery efficiency and order sizes.

Data Fields: Order_ID, Order_Value, Delivery_Time, and Distance_km.

Multivariate Binning:

Order Value: Categorized as LOW, MEDIUM, or HIGH.

Delivery Time: Categorized as Late (≤25 min), On Time (26−40 min), or Early (41−60 min).

Distance: Categorized as Short, Medium, or High.

Frequency Analysis: Uses .value_counts() to identify the distribution of order categories (e.g., identifying that the majority of orders fall into the 'MEDIUM' and 'HIGH' value brackets).
