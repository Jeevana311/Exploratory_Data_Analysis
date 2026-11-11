# Exploratory_Data_Analysis
# Sales Transactions Dataset – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Sales Transactions Dataset using Python. The objective is to understand sales patterns, identify data quality issues, explore relationships between variables, and extract meaningful business insights through statistical analysis and visualizations.

The analysis includes data cleaning, missing value handling, inconsistent data detection, outlier analysis, feature engineering, and data visualization.

## 📊 Dataset Description

The dataset contains **260 records and 9 columns** after removing redundant product ID columns.

| Column Name | Description | Data Type |
|---|---|---|
| transaction_id | Unique identifier for each transaction | Object |
| region | Geographical region where the sale occurred | Object |
| product_id | Identifier of the product sold | Numeric |
| sales_amount | Total sales amount for the transaction | Float |
| date | Date of the transaction | Date |
| units_sold | Number of units sold | Float |
| unit_price | Price per unit of the product | Float |
| discount_pct | Discount percentage applied | Float |
| store_id | Identifier of the store | Object |

## 🛠️ Technologies Used

- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical data visualization
- Jupyter Notebook – Interactive analysis

## 🔍 EDA Workflow

### 1. Data Understanding
- Examining dataset dimensions using `shape`.
- Understanding column names and data types.
- Generating descriptive statistics.
- Identifying unique values.

### 2. Data Cleaning
- Identifying and handling duplicate records.
- Detecting missing values.
- Handling missing categorical and numerical values.
- Identifying redundant columns.

### 3. Handling Inconsistent Data
- Standardizing region names.
- Correcting spelling mistakes.
- Cleaning inconsistent store identifiers.
- Checking invalid and negative values.

### 4. Outlier Detection
- Detecting outliers using the Interquartile Range (IQR) method.
- Visualizing outliers using boxplots.
- Evaluating unusual values in sales amount, units sold, unit price, and discount percentage.

### 5. Feature Engineering
- Extracting year, month, and day from transaction dates.
- Creating additional sales-related features.
- Calculating expected sales after discounts.

### 6. Univariate Analysis
- Analyzing individual numerical and categorical variables.
- Understanding distributions and frequency counts.
- Identifying frequently occurring products and regions.

### 7. Bivariate Analysis
- Region-wise sales analysis.
- Product-wise sales analysis.
- Store-wise sales analysis.
- Relationship between units sold and sales amount.
- Relationship between discounts and sales.

### 8. Multivariate Analysis
- Correlation analysis.
- Correlation heatmap.
- Pairwise relationships between numerical variables.

## 📈 Data Visualization

The following visualizations are used:

- Bar Charts
- Histograms
- Boxplots
- Scatterplots
- Line Charts
- Countplots
- Correlation Heatmaps
- Pairplots

## 🎯 Key Analysis Objectives

The project aims to answer the following business questions:

1. Which region generates the highest sales?
2. Which products have the highest sales?
3. Which store generates the highest revenue?
4. What are the monthly sales trends?
5. How do discounts affect sales?
6. Which products have the highest demand?
7. What is the relationship between units sold and sales amount?
8. Which regions contribute the most to overall revenue?


## 💡 Expected Outcomes

- Improved understanding of sales transaction data.
- Identification of missing and inconsistent data.
- Detection of unusual sales patterns and outliers.
- Understanding of regional, product, and store-wise sales performance.
- Identification of important business trends.
- Data-driven insights to support business decisions.

## 🏁 Conclusion

This project demonstrates the application of Exploratory Data Analysis techniques to a sales transaction dataset. By performing data cleaning, statistical analysis, and visualization, the project aims to uncover useful patterns and relationships within sales data and provide meaningful insights for business decision-making.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Sales and Business Analytics  
**Language:** Python
