# E-Commerce Sales Data Analysis | Excel

## 📌 Project Overview

This project focuses on **E-Commerce Sales Data Analysis** using Microsoft Excel. The main objective is to analyze sales transactions, identify business trends, check data quality, and generate meaningful insights to support data-driven decision-making.

As an aspiring Data Analyst, I completed this project to develop practical skills in data cleaning, data validation, sales analysis, and business reporting.

## 🎯 Project Objectives

- Analyze overall sales performance and transaction trends.
- Identify the best-performing and lowest-performing product categories.
- Compare sales performance across different regions.
- Analyze customer payment method preferences.
- Perform data quality checks and identify missing values.
- Validate sales calculations and identify inconsistencies.
- Provide actionable business recommendations based on the findings.

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- Data Cleaning and Validation
- Sales Data Analysis
- Excel Formulas
- Business Reporting

## 📂 Dataset Description

The dataset contains **2,000 sales transactions** covering the period from 14 October 2023 to 13 October 2025.

| Metric | Details |
|---|---:|
| Total Transactions | 2,000 |
| Unique Customers | 492 |
| Product IDs | 100 |
| Stores | 20 |
| Total Recorded Sales | 2,175,266.50 |
| Units Sold | 4,958 |
| Average Transaction Value | 1,087.63 |

### Key Dataset Columns

- `Sales_ID` – Unique sales transaction identifier
- `Order_Date` – Date of the transaction
- `Customer_ID` – Customer identifier
- `Product_ID` – Product identifier
- `Store_ID` – Store identifier
- `Quantity` – Number of units sold
- `Unit_Price` – Price per unit
- `Discount` – Discount applied to the transaction
- `Payment_Type` – Payment method used
- `Total_Amount` – Recorded transaction amount
- `Customer_Name` – Customer name
- `Category` – Product category
- `Region` – Sales region

## 🔍 Data Cleaning and Validation

The following data quality checks were performed:

- Checked for duplicate sales IDs and exact duplicate records.
- Identified missing values in the `Discount` column.
- Compared calculated transaction amounts with recorded `Total_Amount` values.
- Reviewed the date range to identify incomplete reporting periods.
- Identified records requiring further validation before financial reporting.

**Data quality findings:**
- Four transactions have missing discount values: `SALE26`, `SALE52`, `SALE58`, and `SALE259`.
- No duplicate `Sales_ID` values or exact duplicate rows were identified.
- In 318 of the 1,996 records with a populated discount, the calculated amount differed from the recorded amount by more than 1. The calculation rule requires further investigation.

## 📊 Key Findings

### 1. Category Performance

| Category | Total Sales | Sales Share |
|---|---:|---:|
| Sports | 541,973.50 | 24.9% |
| Electronics | 504,311.20 | 23.2% |
| Home | 427,296.50 | 19.6% |
| Clothing | 379,235.00 | 17.4% |
| Beauty | 322,450.30 | 14.8% |

**Insight:** Sports generated the highest sales, followed by Electronics. Beauty recorded the lowest sales among the five categories.

### 2. Regional Performance

| Region | Total Sales | Sales Share |
|---|---:|---:|
| North | 647,345.30 | 29.8% |
| South | 635,212.10 | 29.2% |
| East | 622,032.50 | 28.6% |
| West | 270,676.60 | 12.4% |

**Insight:** North contributed the largest share of total sales. West had the lowest total sales but the highest average transaction value of 1,161.70.

### 3. Payment Method Analysis

| Payment Method | Total Sales |
|---|---:|
| PayPal | 756,718.90 |
| Credit Card | 714,844.40 |
| COD | 703,703.20 |

**Insight:** PayPal generated the highest sales value, while Credit Card and Cash on Delivery (COD) also contributed significantly.

### 4. Monthly Sales Trend

March 2025 was the strongest month in the dataset, recording total sales of **107,589.00**. October 2025 contains data only through 13 October and should be treated as a partial month.

## 💡 Business Recommendations

- Prioritize inventory availability and targeted promotions for Sports and Electronics.
- Investigate opportunities to increase sales volume in the West region.
- Maintain strong sales coverage in the North, South, and East regions.
- Continue offering PayPal, Credit Card, and COD while monitoring payment costs and customer preferences.
- Verify missing discount values and investigate differences between calculated and recorded transaction amounts.
- Compare monthly sales using complete months to ensure fair performance comparisons.

## 📈 Skills Demonstrated

- Data Cleaning and Validation
- Exploratory Data Analysis (EDA)
- Excel Data Analysis
- Sales and Revenue Analysis
- Category and Regional Performance Analysis
- Data Quality Assessment
- Business Insights and Recommendations
- Analytical Thinking and Problem-Solving

## 📁 Project Files

Add the following files to this repository:

- `Ecommerce_Sales_Dataset.xlsx` – Original dataset
- `README.md` – Project documentation
- `Sales_Data_Analysis_Summary.docx` – One-page findings and recommendations
- `Sales_Analysis.xlsx` – Cleaned dataset and analysis, if available

*Update the filenames above to match the actual files uploaded to your repository.*

## 🏁 Conclusion

This project demonstrates how sales data can be examined to identify top-performing product categories, regional sales patterns, payment method performance, and data quality issues. The findings can help businesses make better inventory, marketing, and operational decisions.

This project is part of my learning journey as an **Aspiring Data Analyst**, where I am building practical skills in data analysis and developing my professional portfolio.

## 👤 Author

**Aspiring Data Analyst**

Skills: Microsoft Excel | Data Cleaning | Data Analysis | Business Insights

