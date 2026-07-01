# 📊 HR Analytics Dashboard

An interactive **Power BI dashboard** built to analyze workforce data, employee attrition, salary trends, and HR performance metrics. This project demonstrates end-to-end Business Intelligence development, from data transformation to interactive dashboard design.

---

## 🚀 Project Overview

The objective of this project is to help HR professionals identify workforce trends and factors influencing employee attrition through data-driven insights.

The dashboard consolidates employee information into a single interactive report, enabling users to monitor KPIs, explore workforce demographics, analyze departmental performance, and support strategic HR decision-making.

---

## 📷 Dashboard Preview

![Dashboard](dashboard.png)

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI Calculations & Measures |
| Microsoft Excel | Source Dataset |
| Data Modeling | Table Relationships |
| Power BI Visualizations | Interactive Reporting |

---

## 📂 Dataset

The dashboard is built using an HR employee dataset containing over **1,400 employee records** with information including:

- Employee Demographics
- Department
- Job Role
- Monthly Income
- Education
- Job Satisfaction
- Performance Rating
- Years at Company
- Attrition Status
- Overtime
- Business Travel

---

# Dashboard Pages

### Executive Summary

Provides a high-level overview of workforce performance through KPI cards and key business metrics.

### Employee Demographics

Analyzes workforce distribution by:

- Gender
- Age
- Education
- Marital Status
- Department

### Attrition Analysis

Identifies patterns in employee turnover across:

- Departments
- Job Roles
- Age Groups
- Salary Bands
- Education Fields
- Overtime
- Business Travel

### Compensation Analysis

Provides insights into:

- Average Salary
- Salary Distribution
- Salary by Department
- Salary by Job Role

### Employee Satisfaction

Evaluates:

- Job Satisfaction
- Work-Life Balance
- Attrition vs Satisfaction
- Department Comparison

---

## 📈 Key Performance Indicators

| KPI |
|-----|
| Total Employees |
| Active Employees |
| Attrition Count |
| Attrition Rate |
| Average Salary |
| Average Age |
| Average Years at Company |

---

## ✨ Dashboard Features

- Interactive slicers
- Cross-filtering visuals
- Department-wise analysis
- Employee demographics
- Salary distribution
- Attrition analysis
- Job satisfaction insights
- Education field analysis
- Dynamic KPI cards
- Responsive dashboard layout

---

## 📊 Business Insights

The dashboard helps answer questions such as:

- Which departments experience the highest attrition?
- Which job roles have the greatest employee turnover?
- Does overtime increase attrition?
- How does salary relate to employee retention?
- Which education fields show higher attrition rates?
- What is the age distribution of employees leaving the company?
- Which departments have the highest average salary?

---

## ⚙ Data Preparation

The dataset was processed using **Power Query**, including:

- Removing duplicates
- Handling missing values
- Data type corrections
- Column standardization
- Feature engineering
- Data modeling
- Relationship creation

---

## 📐 DAX Measures

Examples of measures created for the dashboard include:

```DAX
Total Employees =
COUNT(Employee[EmployeeID])

Attrition Count =
CALCULATE(
    COUNT(Employee[EmployeeID]),
    Employee[Attrition] = "Yes"
)

Attrition Rate =
DIVIDE(
    [Attrition Count],
    [Total Employees]
)

Average Salary =
AVERAGE(Employee[MonthlyIncome])

Average Age =
AVERAGE(Employee[Age])
```

---

## 📁 Repository Structure

```
HR-Analytics-Dashboard
│
├── Dashboard.pbix
├── Dataset.xlsx
├── README.md
│
├── images
│   └── dashboard.png
│
└── assets
```

---

## 🎯 Skills Demonstrated

- Business Intelligence
- Power BI
- Dashboard Development
- Data Modeling
- Power Query
- DAX
- Data Cleaning
- Data Visualization
- KPI Design
- HR Analytics
- Analytical Thinking

---

## 🔮 Future Improvements

- Predictive Attrition Analysis
- Power BI Service Deployment
- Automated Data Refresh
- Drill-through Employee Profiles
- Row-Level Security (RLS)
- Mobile Dashboard Optimization

---

## 👨‍💻 Author

**Parth Sharma**

Aspiring Business Analyst | Data Analyst

- Power BI
- SQL
- Excel
- DAX
- Power Query
- Business Intelligence

---

⭐ If you found this project helpful, consider giving the repository a star.
