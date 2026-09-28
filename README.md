# DATA ANALYSIS PROJECT – WEEK 1 TO WEEK 7

## Project Overview

This repository contains a collection of data analysis projects completed using Python and popular data analysis libraries. The projects cover data cleaning, exploratory data analysis, visualization, statistical analysis, business insights, financial analysis, healthcare analysis, and student performance analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

# WEEK 1: SUPERSTORE SALES DATA UNDERSTANDING, CLEANING & EXPLORATORY ANALYSIS

## Description

This project focuses on understanding, cleaning, and analyzing the Superstore Sales dataset using Python and Pandas.

## Objectives

- Load the dataset using Pandas.
- Inspect the dataset using head(), info(), and describe().
- Convert Order Date and Ship Date into proper datetime format.
- Clean and standardize categorical attributes such as Category, Sub-Category, and Segment.
- Calculate summary statistics for numerical attributes.

## Workflow

1. Load the dataset.
2. Inspect the dataset structure.
3. Check data types and missing values.
4. Convert date columns into datetime format.
5. Clean categorical attributes.
6. Generate summary statistics.
7. Prepare the cleaned dataset for further analysis.

## Key Outcome

The Superstore Sales dataset was successfully cleaned, processed, and prepared for further exploratory analysis.

---

# WEEK 2: RETAIL SALES VISUALIZATION, RELATIONSHIP ANALYSIS & BUSINESS INSIGHTS

## Description

This project focuses on visualizing retail sales data and analyzing relationships between Sales, Profit, Discount, Quantity, and other numerical attributes.

## Objectives

- Create different visualizations for sales and profit.
- Analyze the relationship between Discount and Profit.
- Identify discount levels that may affect profitability.
- Generate a correlation heatmap.
- Analyze relationships between Sales, Profit, Discount, and Quantity.
- Generate meaningful business insights.

## Visualizations

- Sales by Category – Bar Plot
- Sales Distribution – Histogram
- Profit by Category – Bar Plot
- Sales Distribution by Category – Bar Plot
- Profit Variation Across Categories – Box Plot
- Profit Distribution – Box Plot
- Discount vs Profit – Scatter Plot
- Correlation Heatmap

## Business Insights

- Analyze the impact of discounts on profitability.
- Compare sales and profit across different categories.
- Identify strong and weak-performing categories.
- Study relationships between numerical attributes.
- Support pricing and discount-related decisions through data analysis.

## Key Outcome

Retail sales and profitability were analyzed using different visualization techniques, and meaningful business insights were generated.

---

# WEEK 3: STOCK MARKET PRICE, RETURN & TRADING VOLUME ANALYSIS

## Description

This project focuses on cleaning and analyzing stock market data using Python and Pandas. The analysis includes daily price changes, percentage returns, trading volume trends, anomalous trading days, and statistical analysis of stock returns.

## Objectives

- Load the stock market dataset using Pandas.
- Clean Open, High, Low, Close, and Volume attributes.
- Calculate daily price change using Close - Open.
- Calculate daily percentage return.
- Calculate the 5-day moving average of trading volume.
- Identify anomalous trading days.
- Calculate statistical measures of stock returns.
- Visualize trading volume and return distributions.

## Visualizations

- Trading Volume Trend – Line Chart
- 5-Day Moving Average of Volume – Line Chart
- Anomalous Trading Days – Line and Scatter Plot
- Daily Return Distribution – Histogram

## Statistical Analysis

- Mean
- Median
- Variance
- Standard Deviation

## Key Outcome

Stock price movements, daily returns, trading volume trends, and return statistics were successfully analyzed.

---

# WEEK 4: SHOPIFY STOCK PRICE, MOVING AVERAGE & RETURN ANALYSIS

## Description

This project focuses on analyzing Shopify stock market data using Python, Pandas, Matplotlib, and Seaborn.

The analysis includes OHLC prices, trading volume, daily percentage returns, moving averages, return distributions, and volatility analysis.

## Objectives

- Load and clean the Shopify stock dataset.
- Clean Open, High, Low, Close, and Volume attributes.
- Calculate daily percentage returns.
- Visualize OHLC prices over time.
- Analyze trading volume trends.
- Calculate 20-day and 50-day moving averages.
- Compare closing prices with moving averages.
- Analyze daily return distributions.
- Identify high-volatility days.

## Visualizations

- OHLC Prices Over Time – Line Chart
- Trading Volume Over Time – Line Chart
- Closing Price with 20-Day Moving Average – Line Chart
- Closing Price with 50-Day Moving Average – Line Chart
- Closing Price with 20-Day and 50-Day Moving Averages – Line Chart
- Daily Return Distribution – Histogram and KDE Plot

## Statistical Analysis

- Mean
- Variance
- Standard Deviation
- Highest Closing Price
- Lowest Closing Price
- Average Trading Volume
- Maximum Trading Volume

## Key Outcome

Shopify stock prices, returns, trading volume, moving averages, and volatility were analyzed and summarized.

---

# WEEK 5: HEALTHCARE DATA CLEANING, ADMISSION ANALYSIS & DEMOGRAPHIC SEGMENTATION

## Description

This project focuses on cleaning and analyzing the Healthcare dataset using Python and Pandas.

The analysis includes missing value handling, date conversion, admission classification, hospital stay duration, billing analysis, and patient demographic segmentation.

## Objectives

- Load and inspect the healthcare dataset.
- Identify and handle missing values.
- Convert Date of Admission and Discharge Date into datetime format.
- Categorize admissions into Emergency, Elective, and Urgent.
- Calculate hospital stay duration.
- Analyze Billing Amount.
- Analyze Hospital Stay Days.
- Segment patients based on Medical Condition.

## Data Analysis

- Missing Values
- Admission Urgency
- Billing Amount
- Hospital Stay Duration
- Medical Condition
- Age Demographics

## Key Outcome

The healthcare dataset was successfully cleaned and analyzed to understand admission patterns, billing information, hospital stay duration, and patient demographics.

---

# WEEK 6: HEALTHCARE DATA VISUALIZATION, COST RELATIONSHIP & POLICY INSIGHTS

## Description

This project focuses on visualizing and analyzing healthcare data using Python, Pandas, Matplotlib, and Seaborn.

The analysis includes billing amounts, insurance providers, medical conditions, patient admission trends, hospital stay duration, and relationships between age and total medical cost.

## Objectives

- Load and clean the healthcare dataset.
- Convert date attributes into proper datetime format.
- Convert Billing Amount into numeric format.
- Handle missing required values.
- Compare billing amounts across medical conditions and insurance providers.
- Analyze patient admission trends.
- Calculate hospital stay duration.
- Generate a correlation matrix and heatmap.

## Visualizations

- Billing Amount by Medical Condition and Insurance Provider – Stacked Bar Chart
- Billing Amount by Medical Condition – Violin Plot
- Billing Amount by Insurance Provider – Violin Plot
- Patient Admissions Over Time – Line Chart
- Monthly Patient Admissions – Line Chart
- Age, Stay Duration and Total Medical Cost – Correlation Heatmap

## Healthcare Analysis

- Compare billing amounts across medical conditions.
- Analyze billing differences between insurance providers.
- Study patient admission trends over time.
- Analyze monthly admission patterns.
- Calculate hospital stay duration.
- Analyze relationships between Age, Stay Duration, and Total Medical Cost.

## Key Outcome

Healthcare billing, admission trends, hospital stay duration, and cost relationships were analyzed using statistical and visualization techniques.

---

# WEEK 7: STUDENT PERFORMANCE DATA CLEANING, STATISTICAL ANALYSIS & OUTLIER DETECTION

## Description

This project focuses on cleaning and analyzing the Student Performance dataset using Python, Pandas, and NumPy.

The analysis includes categorical data cleaning, statistical analysis of subject scores, total marks calculation, percentage calculation, and performance outlier detection.

## Objectives

- Load the Student Performance dataset.
- Inspect the dataset and identify missing values.
- Clean and standardize categorical attributes.
- Calculate statistical measures for Math, Reading, and Writing scores.
- Calculate total marks.
- Calculate percentage performance.
- Detect performance outliers using the IQR method.

## Statistical Analysis

The following statistical measures were calculated for Math, Reading, and Writing scores:

- Mean
- Median
- Standard Deviation
- Q1
- Q3

## Performance Analysis

- Calculate total marks for each student.
- Calculate percentage performance.
- Compare statistical measures across subjects.
- Identify unusual performance values using the IQR method.

## Key Outcome

Student performance was analyzed using statistical measures, calculated performance metrics, and IQR-based outlier detection.

---

# Overall Project Outcomes

Through these seven weeks, the following data analysis skills were developed:

- Data Loading and Inspection
- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- Correlation Analysis
- Business Insight Generation
- Financial Data Analysis
- Healthcare Data Analysis
- Student Performance Analysis
- Outlier Detection

# Conclusion

This project provides practical experience in analyzing different types of datasets using Python. The weekly tasks helped develop skills in data cleaning, exploratory analysis, visualization, statistical analysis, and extracting meaningful insights from data.
