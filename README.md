# HR Strategy and Talent Retention Analysis

An HR analytics project developed with Python and Power BI to analyze employee attrition, identify high-risk departments, and support data-driven talent retention strategies.

## Project Overview

Employee attrition can increase recruitment costs, reduce productivity, and affect organizational performance.

This project analyzes HR data to help identify:

- Overall employee attrition
- High-risk departments
- Employee terminations over time
- Attrition by job satisfaction
- Attrition by performance score
- Estimated turnover cost
- Department-level retention priorities

## Tools and Technologies

- Python
- Pandas
- Jupyter Notebook
- Power BI
- DAX
- Data Modeling
- Data Visualization
- Conditional Formatting

## Project Workflow

1. HR data was prepared and processed using Python.
2. The employee, department, and calendar datasets were organized.
3. Relationships between the data tables were created in Power BI.
4. DAX measures were developed for key HR metrics.
5. An interactive three-page Power BI dashboard was designed.
6. High-risk departments and turnover costs were highlighted using visual analysis.

## Dashboard Pages

### 1. Executive Summary

Provides an overview of the most important HR metrics:

- Employee Count: 500
- Attrition Rate: 19.60%
- Employees Who Left: 98
- Employees Who Stayed: 402
- Estimated Turnover Cost: 1,470,000

### 2. Deep Dive

Analyzes employee attrition by:

- Department
- Job Satisfaction
- Performance Score
- Time
- Attrition Status

### 3. Actionable Insights

Highlights departments that require greater retention attention.

The highest attrition rates were observed in:

- Marketing: 25.00%
- IT: 24.30%
- Finance: 19.23%
- Sales: 16.19%
- HR: 14.42%

Marketing and IT represent the highest-priority departments for further investigation and retention planning.

## Key Findings

- The overall attrition rate is 19.60%.
- 98 out of 500 employees left the organization.
- Marketing has the highest attrition rate.
- IT has the second-highest attrition rate and the highest number of terminations.
- The estimated total turnover cost is 1,470,000.
- Department-level analysis can help HR prioritize retention initiatives.

## Repository Structure
```text
HR-Strategy-and-Talent-Retention-Analysis/
├── images/
│   ├── 01_executive_summary.png
│   ├── 02_deep_dive.png
│   └── 03_actionable_insights.png
├── app.ipynb
├── dashboard.pbix
├── calendar.csv
├── hr_departments.csv
├── hr_employees.csv
└── README.md
