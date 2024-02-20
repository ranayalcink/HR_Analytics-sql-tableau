# SQL Project - HR Data Analytics

## Business Problem

**Objective:** Extract Actionable Insights from Employee Database

In this data analysis project, the business problem revolves around unraveling intricate patterns within the company's employee database. Key objectives include understanding workforce demographics, managerial structures, and discerning potential gender-based salary disparities.

**Used skills:**

- SQL Querying
- Data Analysis
- Data Visualization (Tableau)
- Stored Procedure Development
- Database Management
- Data Aggregation
- Conditional Logic
- Dynamic Parameterization
- Problem Solving
- Tableau Dashboard Development
- Interactive Data Exploration

## Technical Approach

### Chart 1: Gender Breakdown Over Time

**SQL Query:**
- Utilizes a JOIN operation to combine `t_employees` and `t_dept_emp` tables.
- Extracts calendar year, gender, and employee count.
- Facilitates GROUP BY for aggregating data by year and gender.

### Chart 2: Male and Female Managers Comparison

**SQL Query:**
- Employs subqueries and JOIN operations to link multiple tables (`t_employees`, `t_dept_manager`, `t_departments`) for comprehensive data retrieval.
- Utilizes a CASE statement for categorizing active managers based on their tenure.

### Chart 3: Average Salary Comparison by Gender and Department

**SQL Query:**
- Leverages JOIN operations to integrate salary, employee, and departmental data.
- Applies GROUP BY for aggregating data by department, gender, and calendar year.
- Implements the HAVING clause to filter results for the specified time frame.

### Stored Procedure: Salary Filtering

**SQL Stored Procedure:**
- Implements a stored procedure named `filter_salary`.
- Accepts user-defined minimum and maximum salary values.
- Utilizes WHERE clause to filter salary data within the specified range.
- Empowers users to dynamically explore average male and female salaries per department.

## Practical Application

As a data analyst, this project equips stakeholders with actionable insights to inform strategic decision-making. By harnessing the power of SQL queries and a versatile stored procedure, we not only answer predefined questions but also empower users to explore the data autonomously. This approach aligns with the principles of data-driven decision-making, fostering a more inclusive and informed organizational culture.

## Tableau Dashboard
In addition to the SQL analyses, a Tableau dashboard was created to visually represent the key insights derived from the SQL queries. The dashboard provides an interactive and user-friendly interface for stakeholders to explore the data visually. It complements the SQL-driven analysis by offering a dynamic and intuitive way to interpret the findings.

## Conclusion

The SQL portfolio project exemplifies the value of leveraging data analytics to address real-world business challenges. Through thoughtful analysis and visualization, we have provided a lens into workforce dynamics, leadership structures, and salary trends. As a data analyst, this project reflects a commitment to delivering actionable insights that drive positive change within the organization.
