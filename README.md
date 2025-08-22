# PowerBI--HR_Dashboard

Here we are analysing  the employees' data
to know why and from where, and which age group and which gender are leaving the job most, and why.

1. We have 38 columns, so to decide which column is beneficial and relevant to our dashboard
2. So we are using a pivot table to reduce the number of columns.

HR Attrition Analysis Dashboard
This repository contains the source files for an interactive HR Attrition Analysis Dashboard built using Microsoft Power BI. The dashboard is designed to help HR analysts and management visualize and understand the key factors driving employee attrition within the organization.

The primary goal of this dashboard is to provide actionable insights into employee turnover. By analyzing various demographic, role-based, and satisfaction-related metrics, stakeholders can identify high-risk groups, understand underlying causes of attrition, and develop targeted retention strategies.

Key Metrics & KPIs
The dashboard provides a high-level summary of the workforce through the following key performance indicators:

Total Employee Count: 1,423

Total Attrition Count: 230

Average Employee Age: 37

Average Salary: $6.5K

Average Tenure (Years): 7.0



Features & Visualizations
The dashboard is composed of several interactive visualizations that allow for deep-dive analysis:

Attrition by Gender: A breakdown of the total employee count by gender, providing context for gender distribution in the workforce.

Attrition by Education: A donut chart illustrating the educational background of employees who have left the company. Key fields include Life Sciences, Medical, Marketing, and Technical Degrees.

Attrition by Age Group: A column chart that highlights the attrition rates across different age brackets, showing that the 26-35 age group has the highest number of attritions.

Attrition by Job Satisfaction (Matrix): A detailed table that cross-references attrition numbers by JobRole and JobSatisfaction level (on a scale of 1-4). This helps pinpoint dissatisfaction in specific roles.

Attrition by Average Salary: A bar chart analyzing employee distribution across different salary brackets. This can be used to investigate the correlation between compensation and attrition.

Attrition by Average Year: An area chart showing the trend of attrition based on the employee's tenure. It indicates that attrition is highest within the first few years of employment.

Attrition by Job Type: A horizontal bar chart that displays the total number of employees in each job role, highlighting roles like Sales Executive and Research Scientist which have the largest headcounts.

Interactive Slicers: The dashboard includes slicers for Departments (Human Resources, Research & Development, Sales) allowing users to filter the entire report for a department-specific view.

Potential Future Improvements
Predictive Analysis: Integrate a Python or R script to build a machine learning model that predicts the likelihood of an employee leaving.

Exit Interview Analysis: Incorporate qualitative data from exit interviews using text analytics to uncover more nuanced reasons for attrition.

Row-Level Security (RLS): Implement RLS to allow managers to view data only for their respective teams.

Time-Series Analysis: Add a dedicated page for analyzing attrition trends over months or quarters to identify seasonal patterns.
