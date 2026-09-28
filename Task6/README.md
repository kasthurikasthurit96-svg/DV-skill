# TASK-6 Healthcare Data Visualization, Cost Relationship & Policy Insights

##  Project Overview

This project focuses on visualizing and analyzing healthcare data to understand **medical costs, patient admissions, hospital stay duration, medical conditions, and insurance providers**.

Python is used to create charts, analyze relationships between variables, and generate healthcare management insights.

##  Objectives

* Compare billing amounts across medical conditions.
* Compare billing amounts across insurance providers.
* Create stacked bar charts and violin plots.
* Analyze patient admissions over time.
* Identify periods with higher patient admissions.
* Study relationships between age, hospital stay, and billing amount.
* Generate an executive summary.
* Provide data-based healthcare management recommendations.

##  Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab
* CSV Dataset

##  Dataset Attributes

Important attributes used in the analysis include:

| Attribute            | Description                          |
| -------------------- | ------------------------------------ |
| `Age`                | Patient age                          |
| `Medical Condition`  | Patient's medical condition          |
| `Insurance Provider` | Patient's insurance provider         |
| `Date of Admission`  | Date when the patient was admitted   |
| `Discharge Date`     | Date when the patient was discharged |
| `Billing Amount`     | Total medical billing amount         |
| `Stay_Days`          | Number of days spent in the hospital |

##  Billing Analysis

Billing amounts are analyzed across:

* Medical conditions
* Insurance providers

A **stacked bar chart** is used to compare total billing amounts across medical conditions and insurance providers.

##  Violin Plot Analysis

Violin plots are created to understand the distribution of billing amounts.

The analysis includes:

* Billing amount by medical condition
* Billing amount by insurance provider

Violin plots help show the spread and distribution of the billing values.

##  Patient Admission Trend

The admission date is converted into a proper datetime format.

Monthly patient admissions are calculated and displayed using a **line chart**.

This helps identify periods where patient admissions increase or decrease.

##  Hospital Stay Duration

Hospital stay duration is calculated using:

```text
Stay Days = Discharge Date - Date of Admission
```

This value is used to study the relationship between hospital stay and medical costs.

## 🔗 Correlation Analysis

A correlation matrix is created using:

* Age
* Stay Duration
* Billing Amount

Correlation values help identify the strength and direction of linear relationships between these variables.

A heatmap is used to visualize the correlation matrix.

**Note:** Correlation indicates association and does not by itself establish causation.

##  Executive Summary

The project summarizes:

* Total number of patients
* Average billing amount
* Average hospital stay
* Average patient age
* Most common medical condition
* Most common insurance provider
* Peak admission period

##  Healthcare Management Recommendations

Based on the exploratory analysis:

1. Monitor medical conditions associated with higher billing amounts.
2. Analyze billing differences across insurance providers.
3. Prepare additional resources during periods of higher patient admissions.
4. Monitor hospital stay duration for better bed and resource planning.
5. Use cost and admission trends to support healthcare resource management.
6. Regularly review high-cost cases to understand major healthcare expenditure patterns.

These are **data-analysis recommendations** and should be evaluated alongside clinical, operational, and regulatory considerations before implementation.

##  Project Workflow

```text
Healthcare Dataset
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Calculate Hospital Stay
       ↓
Billing Analysis
       ↓
Medical Condition Analysis
       ↓
Insurance Provider Analysis
       ↓
Stacked Bar Chart
       ↓
Violin Plots
       ↓
Monthly Admission Analysis
       ↓
Correlation Matrix
       ↓
Executive Summary
       ↓
Management Recommendations
```

##  How to Run

1. Open **Google Colab**.
2. Upload the healthcare CSV dataset.
3. Load the dataset using Pandas.
4. Run the data cleaning code.
5. Calculate hospital stay duration.
6. Run the visualization codes separately.
7. Analyze the correlation matrix.
8. Review the executive summary and recommendations.

##  Conclusion

This project demonstrates how Python can be used for **healthcare data visualization and exploratory analysis**. The analysis provides insights into billing patterns, insurance providers, medical conditions, patient admission trends, hospital stay duration, and relationships between patient characteristics and medical costs.

## Plot Overview
<img width="1255" height="758" alt="image" src="https://github.com/user-attachments/assets/46dd6640-d8d2-4c66-8c30-3a8e210a63ac" />

<img width="1291" height="719" alt="image" src="https://github.com/user-attachments/assets/11d082c0-2084-43fb-8313-7b12626b756f" />

<img width="789" height="660" alt="image" src="https://github.com/user-attachments/assets/09c1d251-275a-4e8d-a8c4-939798fdf94b" />


## 👩‍💻 Author

**Kasthuri T**

BCA Student
