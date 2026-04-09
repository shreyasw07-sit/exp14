# exp14
## 📑 Experiment 14: Data Binning & Formatting
Author: Shreyas Wani
PRN:25070123131

Objective: To transform raw numerical data into structured categorical groups (binning) and standardize data types and text formats.

## 🛠️ Technologies Used
Python 3 🐍

Pandas: For DataFrame manipulation and categorical grouping.

NumPy: For numerical support.

## 📊 Key Operations Demonstrated
### 1. Data Binning (Discretization) 🗑️

This technique is used to group continuous numerical values into discrete "bins" or categories for easier analysis.

Price Binning: Categorizing products into Low, Medium, and High price ranges based on specific thresholds (0–10k, 10k–30k, 30k–60k).

Units Sold Binning: Segmenting sales performance into Low Sales, Medium Sales, and High Sales.

Delivery Logistics: Categorizing delivery times as On Time, Delayed, or Critical.

### 2. Data Formatting & Cleaning 🧹

Standardizing the appearance and structure of the dataset to ensure consistency.

Type Conversion: Converting integer columns (like Units_Sold) to floating-point numbers using .astype(float).

String Normalization: Converting all product names to UPPERCASE for uniformity.

Numerical Precision: Rounding numerical values (like Price) to two decimal places.

### 3. Data Exploration 🔍

Sorting: Organizing data in both ascending and descending order based on specific columns like Price.

Unique Value Identification: Extracting unique categories created during the binning process.

## 📋 Example Datasets
### Retail Dataset 🛒

Product	Price	Units Sold	Price Category
LAPTOP	55000	25.0	High
MOBILE	20000	60.0	Medium
HEADPHONES	2000	80.0	Low
### Logistics Dataset 🚚

Order ID	Order Value	Delivery Time	Status
O1	250	30	Delayed
O3	120	25	On Time
O4	600	60	Critical
## 🚀 How to Use
Load the Notebook: Open exp14.ipynb in Google Colab or any Jupyter environment.

Initialize Data: Run the first code cell to create the sample DataFrames.

Execute Transformations: Run the subsequent cells to see how pd.cut() transforms raw numbers into labeled categories.
