📊 HR Analytics Case Study – Atlas Labs
🏢 Project Overview
This case study explores HR analytics for Atlas Labs, a tech company, aiming to:

Monitor key employee metrics such as performance, satisfaction, and salary.

Understand the factors impacting employee attrition and provide actionable insights.

🧱 Part 1: Data Modeling
📌 Requirements
Track and visualize employee KPIs.

Detect patterns and trends influencing attrition.

Create an efficient data model for analysis and performance.

🔗 Data Sources & Connections
Employee performance data

Satisfaction and rating levels

Education, demographics, and attrition status

Imported via Excel/CSV into Power BI

🔄 Data Transformation
Steps performed using Power Query:

Removed nulls and handled blank values (replaced with 0)

Standardized date and numeric formats

Derived fields:

Tenure from start date

Age Group segmentation

Attrition Flag (1 = Left, 0 = Active)

🧩 Data Model (Snowflake Schema)
Fact Table:

Performance_Rating

Dimension Tables:

Employee

Satisfaction_Level

Rating_Level

Education_Level

Date
