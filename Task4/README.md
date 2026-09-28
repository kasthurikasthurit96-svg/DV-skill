# TASK-4 Shopify Stock Visualization, Time-Series Analysis & Financial Insights

##  Project Overview

This project analyzes **Shopify stock market data** using Python. It focuses on visualizing stock prices and trading volume, identifying price trends using moving averages, analyzing daily returns, and finding high-volatility periods.

The analysis is performed using **Google Colab, Pandas, Matplotlib, and Seaborn**.

##  Objectives

* Visualize Shopify OHLC stock prices over time.
* Analyze trading volume.
* Calculate 20-day and 50-day moving averages.
* Compare moving averages with daily closing prices.
* Calculate daily stock returns.
* Analyze daily return distributions using histogram and KDE plots.
* Identify high-volatility periods.
* Generate a financial summary of the stock.

##  Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab
* CSV Dataset

##  Dataset

The dataset contains historical Shopify stock information.

Important attributes include:

* **Date** – Trading date
* **Open** – Opening price
* **High** – Highest price of the day
* **Low** – Lowest price of the day
* **Close** – Closing price
* **Volume** – Number of shares traded

##  OHLC Visualization

OHLC stands for:

* **Open** – Opening stock price
* **High** – Highest price
* **Low** – Lowest price
* **Close** – Closing stock price

Line plots are created to understand how Shopify's stock price changes over time.

##  Trading Volume Analysis

Trading volume is plotted over time to understand changes in market activity.

Higher trading volume indicates more shares were traded during that period.

##  Moving Average Analysis

Two moving averages are calculated:

### 20-Day Moving Average

Represents the average closing price over the previous 20 trading days.

### 50-Day Moving Average

Represents the average closing price over the previous 50 trading days.

These moving averages are plotted along with the daily closing price to identify general price trends.

##  Daily Return Analysis

Daily return is calculated using:

```text
Daily Return = ((Today Close - Previous Close) / Previous Close) × 100
```

Daily returns help measure the day-to-day percentage change in the stock price.

##  Histogram and KDE Analysis

A histogram and KDE plot are created for daily returns.

They help analyze the distribution of returns and check whether the distribution is approximately normal or shows **fat-tailed behavior**.

Fat tails indicate that unusually large positive or negative returns occur more frequently than a simple normal distribution would suggest.

##  Volatility Analysis

Daily return standard deviation is used as a measure of daily volatility.

High-volatility periods are identified when the return deviates significantly from the average return.

In this project, a threshold of approximately **2 standard deviations** from the mean is used to identify unusual return movements.

##  Financial Summary

The project generates a summary containing:

* Start date
* End date
* Starting closing price
* Ending closing price
* Highest price
* Lowest price
* Average closing price
* Average daily return
* Daily volatility
* Number of high-volatility days
* Highest daily gain
* Highest daily loss

##  Project Workflow

```text
Upload Shopify Stock Dataset
          ↓
Read Dataset
          ↓
Check Dataset Structure
          ↓
Clean Missing Values
          ↓
Convert Date Format
          ↓
Sort Data by Date
          ↓
Calculate Daily Returns
          ↓
Calculate 20-Day Moving Average
          ↓
Calculate 50-Day Moving Average
          ↓
Visualize OHLC Prices
          ↓
Visualize Trading Volume
          ↓
Analyze Return Distribution
          ↓
Identify High-Volatility Periods
          ↓
Generate Financial Summary
```

##  How to Run

1. Open **Google Colab**.
2. Create a new notebook.
3. Upload the Shopify stock CSV file.
4. Run the Python code.
5. View the generated plots and financial summary.

## Plot Overview
<img width="1072" height="596" alt="Screenshot 2026-09-23 192320" src="https://github.com/user-attachments/assets/eb168eac-f6fe-4a8f-a512-ecf52008a756" />

<img width="1074" height="589" alt="Screenshot 2026-09-23 192305" src="https://github.com/user-attachments/assets/e0b364a7-d4ad-49c3-a5d2-abf0660313ad" />

<img width="1067" height="589" alt="Screenshot 2026-09-23 192249" src="https://github.com/user-attachments/assets/9bc312e2-41a9-461b-8984-00591dd0c14b" />

<img width="1455" height="689" alt="Screenshot 2026-09-23 192235" src="https://github.com/user-attachments/assets/d3862fc0-6b35-43a0-b188-17545fb74b1e" />

<img width="1266" height="600" alt="Screenshot 2026-09-23 192214" src="https://github.com/user-attachments/assets/4382f4b0-6357-470c-a291-acd5c724c647" />

<img width="1279" height="692" alt="Screenshot 2026-09-23 192156" src="https://github.com/user-attachments/assets/0de237b0-ee91-468f-8f4b-634c17820bf1" />


##  Conclusion

This project demonstrates how Python can be used for **stock market visualization and time-series analysis**. Moving averages help examine price trends, while daily return distributions and volatility analysis provide information about the variability of stock prices over time.

##  Author

**Kasthuri T**

BCA Student
