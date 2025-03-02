# Excel Functions Learning Module

This README details various tasks we perform using Excel, specifically tailored for data analysis related to employee management and salary processing. The document outlines how to use specific Excel functions to answer business questions effectively.
Below is a sample of the dataset that was analyzed:

![image](https://github.com/user-attachments/assets/a7bab8e0-fcfe-49da-b0e1-6424a26c689f)


## 📊 Data Analysis Tasks Overview

### 1. Total Salary and Headcount by Department
- **Function(s)**: `SUMIF()`, `COUNTIF()`
- **Purpose**: Calculate the total salary and count the number of employees in each department.

![image](https://github.com/user-attachments/assets/e02b4039-2339-4c20-a83f-dc949da357de)

### 2. Average Salary by Department
- **Function(s)**: `AVERAGEIF()`, `AVERAGEIFS()`
- **Purpose**: Determine the average salary within each department.

### 3. Employees Earning Over $100k
- **Function(s)**: `FILTER()`, `CHOOSECOLS()`
- **Purpose**: Identify all employees with salaries exceeding $100,000.

### 4. High-Earning Female Employees
- **Function(s)**: `FILTER()`
- **Purpose**: Filter all female employees earning more than $100,000.

![image](https://github.com/user-attachments/assets/46bbbaba-2a26-423a-9125-da67d54d7f47)


### 5. Recent High Earners
- **Function(s)**: `FILTER()`
- **Purpose**: Find all employees who earn more than $100k and joined in 2020 or after.

### 6. Salary Extremes and Top Earners
- **Function(s)**: `MIN()`, `MAX()`, `LARGE()`, `SORT()`, `TAKE()`
- **Purpose**: Identify the lowest, highest, and top 5 salaries.

### 7. Gender-Specific Salary Analysis
- **Function(s)**: `MINIFS()`, `MAXIFS()`
- **Purpose**: Calculate the lowest, highest, and top 5 salaries by gender.

![image](https://github.com/user-attachments/assets/4a51bf05-7a32-4087-a950-56789a4d8049)

### 8. Departments List
- **Function(s)**: `UNIQUE()`, `COUNTA()`, `SORT()`
- **Purpose**: Generate a list of all departments.

### 9. Single Cell Department List
- **Function(s)**: `TEXTJOIN()`
- **Purpose**: Combine all department names into one cell, separated by commas.

### 10. Employee Lookup
- **Function(s)**: `VLOOKUP()`, `INDEX()`, `MATCH()`
- **Purpose**: Retrieve detailed information about employees based on specific criteria.

### 11. High Salary Lookup
- **Function(s)**: `XLOOKUP()`, `IFERROR()`
- **Purpose**: Find the employee with the highest salary using advanced lookup functions.

### 12. March Joiners
- **Function(s)**: `FILTER()`, `MONTH()`
- **Purpose**: List all employees who joined the company in March.

### 13. Complex Filter: Monday Starters
- **Function(s)**: `FILTER()`, `WEEKDAY()`
- **Purpose**: Identify female employees who started their jobs on a Monday.

### 14. Departmental Report
- **Function(s)**: `UNIQUE()`, `SUMIFS()`, `COUNTIFS()`, `CONDITIONAL FORMATTING`
- **Purpose**: Create a comprehensive report on departmental salaries and headcounts, highlighting deviations from averages.

![image](https://github.com/user-attachments/assets/e923d13f-ec8c-4d0a-8e08-875a7271d81f)

### 15. Median Salary and Gender Ratio Calculation
- **Function(s)**: `MEDIAN()`, custom array formulas
- **Purpose**: Calculate the median salary and female ratio within each department.
