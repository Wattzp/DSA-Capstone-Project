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
1. 🧾 Standardizing Column Names
Renamed location column to region for clarity and alignment with business terminology.

ALTER TABLE employees
RENAME COLUMN location TO region;




