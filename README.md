# 📊 HR Analytics Case Study – Atlas Labs

## 🏢 Project Overview

This case study explores HR analytics for Atlas Labs, a tech company, aiming to:

Monitor key employee metrics such as performance, satisfaction, and salary.

Understand the factors impacting employee attrition and provide actionable insights.

## 🧱 Part 1: Data Modeling

### 📌 Requirements

Track and visualize employee KPIs.

Detect patterns and trends influencing attrition.

Create an efficient data model for analysis and performance.

### 🔗 Data Sources & Connections

Employee performance data

Satisfaction and rating levels

demographics, and attrition status

Imported via CSV into Power BI

### 🔄 Data Transformation

Steps performed using Power Query:

Removed nulls and handled blank values (replaced with 0)

Standardized date and numeric formats

Derived fields:

Tenure from start date

Age Group segmentation

### 🧩 Data Model (Snowflake Schema)

Fact Table: Performance_Rating

Dimension Tables:

Employee

Satisfaction_Level

Rating_Level

Education_Level

Date


## 🎨 Part 2: Report Design


### 🗂️ Layout Structure

Page 1 –  Overview

![1](https://github.com/user-attachments/assets/84565dc4-c22a-4113-9741-e9040b1fbe5c)


Key metrics (Attrition Rate, Avg Satisfaction, Headcount)

Filters: Department

Page 2 – Demographics Breakdown

![2](https://github.com/user-attachments/assets/0fd3e6f7-bdeb-4f68-9fc3-fe5414c95b41)


Age group, Ethnicity, Education

Average salary by group

Page 3 – Performance Tracker

![3](https://github.com/user-attachments/assets/a5846a12-71b4-4bc6-b75c-00e127bd773d)


Scatter plots showing rating vs. satisfaction

Department-level comparisons

Page 4  – Attrition Analysis

![4](https://github.com/user-attachments/assets/2466b58e-7f16-4d4b-904c-83be065b8c04)

Attrition trends over time

High-risk groups (e.g., frequent travelers)


## 📈 Key Insights

👥 Atlas Labs employs 1,470+ employees.

🖥️ The Technology department is the largest.

🔁 Attrition rate is 16% overall.

🧑‍💼 Most employees are aged 20–29.

💵 White ethnicity group has the highest average salaries.

✈️ Frequent travelers show highest attrition rates, despite being only 19% of the workforce.


## 📌 Next Steps

Expand dashboard to include predictive analytics (e.g. logistic regression for attrition risk).

Implement automated refreshes if connected to live HRIS systems.

Perform benchmarking with industry attrition data.


## 🤝 Credits

Prepared by Omar  Mazhar

Junior Data Analyst | Passionate about storytelling with data

🔗 [LinkedIn](https://linkedin.com/in/omarmazhar-bi) 

