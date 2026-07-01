HR Analytics Dashboard | Power BI
📊 Project Overview

The HR Analytics Dashboard is an end-to-end Business Intelligence project developed using Microsoft Power BI to analyze employee workforce data and identify the major factors contributing to employee attrition.

The dashboard transforms raw HR data into meaningful insights through interactive visualizations, KPI cards, and dynamic filtering, enabling HR managers and business leaders to make informed workforce decisions.

The project covers employee demographics, attrition trends, salary analysis, job satisfaction, education background, and department-level performance to support strategic HR planning.

🎯 Business Problem

Employee attrition directly impacts organizational productivity, recruitment costs, and employee morale. HR departments often struggle to identify the primary reasons employees leave due to scattered and unorganized data.

This dashboard addresses that challenge by providing:

Real-time HR performance monitoring
Employee attrition analysis
Workforce demographic insights
Salary and compensation trends
Department performance comparison
Data-driven HR decision support
📷 Dashboard Preview

Insert your dashboard screenshot here

Example:

images/dashboard.png
🛠 Tools & Technologies
Microsoft Power BI
Microsoft Excel
Power Query
DAX (Data Analysis Expressions)
Data Modeling
Data Visualization
Business Intelligence
📂 Dataset

The dataset contains HR employee records including:

Employee ID
Age
Gender
Department
Job Role
Monthly Income
Education
Marital Status
Job Satisfaction
Years at Company
Attrition Status
Overtime
Business Travel
Performance Rating
📌 Key Performance Indicators (KPIs)

The dashboard tracks several important HR metrics:

👥 Total Employees
📉 Employee Attrition Rate
✅ Active Employees
💰 Average Monthly Salary
🎂 Average Employee Age
⏳ Average Years at Company
📊 Attrition Count
📈 Retention Percentage
📊 Dashboard Features
Employee Overview
Total workforce
Active employees
Attrition count
Average employee age
Salary overview
Attrition Analysis

Analyze employee attrition based on:

Department
Job Role
Gender
Age Group
Education Field
Marital Status
Overtime
Business Travel
Salary Analysis
Average monthly income
Salary distribution
Salary comparison by department
Salary comparison by job role
Workforce Demographics
Gender distribution
Age distribution
Education background
Marital status
Department-wise employee count
Job Satisfaction Analysis

Compare employee satisfaction across:

Departments
Job Roles
Education Levels
Attrition Status
Department Performance

Evaluate each department using:

Employee Count
Attrition Rate
Average Salary
Average Age
Job Satisfaction
Interactive Dashboard

The dashboard includes interactive slicers allowing users to filter by:

Department
Gender
Education
Job Role
Attrition
Age Group

All visuals update dynamically based on selected filters.

📈 Insights Generated

Some key business insights include:

Departments with the highest employee attrition
Job roles experiencing maximum turnover
Relationship between salary and employee attrition
Impact of overtime on employee retention
Education fields with higher attrition rates
Workforce age distribution
Gender diversity across departments
Employee satisfaction trends
📚 Data Preparation

The project involved several preprocessing steps:

Removed duplicate records
Handled missing values
Standardized data formats
Created calculated columns
Developed DAX measures
Built relationships between tables
Optimized data model for performance
📐 DAX Measures Used

Examples include:

Total Employees = COUNT(Employee[EmployeeID])

Active Employees =
CALCULATE(
    COUNT(Employee[EmployeeID]),
    Employee[Attrition] = "No"
)

Attrition Count =
CALCULATE(
    COUNT(Employee[EmployeeID]),
    Employee[Attrition] = "Yes"
)

Attrition Rate =
DIVIDE([Attrition Count],[Total Employees],0)

Average Salary =
AVERAGE(Employee[MonthlyIncome])

Average Age =
AVERAGE(Employee[Age])
