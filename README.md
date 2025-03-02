# 🚀 Excel Advanced Functions

Welcome to the Excel Advanced Functions README! This document details various tasks performed using Excel, specifically tailored for data analysis in the realm of employee management and salary processing. It outlines how to utilize specific Excel functions to effectively answer business questions.

🔍 Below is a sample of the dataset that was analyzed:

![Dataset sample image](https://github.com/user-attachments/assets/a7bab8e0-fcfe-49da-b0e1-6424a26c689f)

## 📊 Data Analysis Tasks Overview

### 💼 1. Total Salary and Headcount by Department
- **Function(s)**: `SUMIF()`, `COUNTIF()`
- **Purpose**: To calculate the total salary and count the number of employees in each department.

![Department data image](https://github.com/user-attachments/assets/e02b4039-2339-4c20-a83f-dc949da357de)

### 💵 2. Average Salary by Department
- **Function(s)**: `AVERAGEIF()`, `AVERAGEIFS()`
- **Purpose**: To determine the average salary within each department.

### 💰 3. Employees Earning Over $100k
- **Function(s)**: `FILTER()`, `CHOOSECOLS()`
- **Purpose**: To identify all employees with salaries exceeding $100,000.

### 🚺 4. High-Earning Female Employees
- **Function(s)**: `FILTER()`
- **Purpose**: To filter all female employees earning more than $100,000.

![Female high earners image](https://github.com/user-attachments/assets/46bbbaba-2a26-423a-9125-da67d54d7f47)

### 5. Recent High Earners
- **Function(s)**: `FILTER()`
- **Purpose**: Find all employees who earn more than $100k and joined in 2020 or after.

### 6. Salary Extremes and Top Earners
- **Function(s)**: `MIN()`, `MAX()`, `LARGE()`, `SORT()`, `TAKE()`
- **Purpose**: Identify the lowest, highest, and top 5 salaries.

### 7. Gender-Specific Salary Analysis
- **Function(s)**: `MINIFS()`, `MAXIFS()`
- **Purpose**: Calculated the lowest, highest, and top 5 salaries by gender.

![image](https://github.com/user-attachments/assets/4a51bf05-7a32-4087-a950-56789a4d8049)

### 📁 8. Departments List
- **Function(s)**: `UNIQUE()`, `COUNTA()`, `SORT()`
- **Purpose**: Generate a comprehensive list of all departments within the organization.

### 📋 9. Single Cell Department List
- **Function(s)**: `TEXTJOIN()`
- **Purpose**: Consolidate all department names into a single cell, separated by commas for streamlined viewing.

### 🔍 10. Employee Lookup
- **Function(s)**: `VLOOKUP()`, `INDEX()`, `MATCH()`
- **Purpose**: Retrieve detailed information about employees efficiently using specific search criteria.

### 💵 11. High Salary Lookup
- **Function(s)**: `XLOOKUP()`, `IFERROR()`
- **Purpose**: Identify the employee with the highest salary through advanced lookup functions, ensuring error handling.

### 🗓️ 12. March Joiners
- **Function(s)**: `FILTER()`, `MONTH()`
- **Purpose**: List all employees who commenced their employment in the month of March.

### 13. Complex Filter: Monday Starters
- **Function(s)**: `FILTER()`, `WEEKDAY()`
- **Purpose**: Identified female employees who started their jobs on a Monday.

### 14. Departmental Report
- **Function(s)**: `UNIQUE()`, `SUMIFS()`, `COUNTIFS()`, `CONDITIONAL FORMATTING`
- **Purpose**: Created a comprehensive report on departmental salaries and headcounts, highlighting deviations from averages.

![image](https://github.com/user-attachments/assets/e923d13f-ec8c-4d0a-8e08-875a7271d81f)

### 15. Median Salary and Gender Ratio Calculation
- **Function(s)**: `MEDIAN()`, custom array formulas
- **Purpose**: Calculated the median salary and female ratio within each department.
