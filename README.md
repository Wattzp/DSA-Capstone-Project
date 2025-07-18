# DSA-Capstone-Project

This project delivers a streamlined approach to data management and organizational insights using SQL for backend data transformation and Power BI for front-end visual analytics. It focuses on optimizing workforce data by cleaning, filtering, and generating actionable reports based on gender distribution, departmental structures etc.

# Project Topic:  Palmoria Group HR Analysis

### 🧠 Project Overview
Palmoria Group, a manufacturing giant in Nigeria, is under fire over gender imbalance across its three operating regions. With public perception and future expansion at risk, HR Analytics was activated to address the issue head-on.

### 📂 Data Source
The dataset used in this project was provided directly by the Human Resources department of Palmoria Group. It contains employee-level records including employee names, gender, department, location, rating and salary information across the company’s three operational zones in Nigeria.

### 🎯 Objective
Investigate workforce gender distribution across regions and departments, identify gaps, and support leadership in fostering inclusion.

### 🛠️ Tools & Methods
- SQL: Data cleansing (e.g., null gender/department fix), structure transformations, and aggregation queries

- Power BI: Interactive dashboards using slicers (Region, Department), gender breakdowns, and trend insights

### 🧹 Data Cleaning & Preparation
Before analysis could begin, significant preprocessing was required to ensure data quality, consistency, and accuracy. The following steps were carried out:
1. Standardizing Column Names
Renamed location column to region for clarity and alignment with business terminology.
2. Addressed missing entries in gender and department using:
- Default imputation for key fields
- Manual corrections from known HR records.
3. Uniform Data Formatting
- Salary, rating, and bonus fields converted to proper number formats
- Categorical entries (e.g., performance ratings, departments) standardized to eliminate typos or mismatched spelling.
4. Bonus Rule Integration
- Linked the bonus percentage matrix from your Excel file into Power BI and SQL queries
-Prepared dynamic lookups to calculate bonuses based on department + performance rating.

# DASHBOARD
![Palmoriadashboard](https://github.com/user-attachments/assets/9b79ea48-4b76-404e-ad6f-7034f58924c7)

## 🎯 Summary Insights:
- Overall gender balance across departments is impressive
- Female employees score better in performance ratings
- South West region draws the highest salary payout
- Gender pay gap exists, but slightly reversed in favor of females for average salary.

## 🔧 Recommendation:
1. Gender Equity Audit by Region & Department
- Investigate hiring, promotion, and pay raise practices
- Ensure women in high-performing roles are progressing to high-paying regions
2. Introduce Performance-Based Bonus Enhancement
- Adjust bonus rates to better reward "Very Good" ratings
- Consider tiered percentage increases to motivate excellence
3. Leadership Acceleration for Female Talent
- Launch mentorship & advancement programs targeting underrepresented departments
- Track promotion outcomes with quarterly dashboards
4. Transparency in Pay & Recognition
- Publish anonymized salary range benchmarks by role and gender
- Incorporate visual dashboards into HR review processes.








