# Module 07 Challenge - Pewlett-Hackard Analysis - SQL

## Overview

In the coming years, many employees will be eligible for retirement at Pewlett-Hackard.

In order to better prepare for this eventuality as a company, Bobby and I were tasked
with compiling a set of summary data and an executive report about Pewlett-Hackard's
aging workforce.

### Deliverables:
1. The Number of Retiring Employees by Title
2. The Employees Eligible for the Mentorship Program
3. This written report

### Resources

- Software: PostgreSQL 11 (Input/Output, and Queries processed via pgAdmin 4)
- Data: This Analysis and Report was compiled using all Internal Company Data, Provided by Management:
	`departments.csv`
	`dept_emp.csv`
	`dept_manager.csv`
	`employees.csv`
	`salaries.csv`
	`titles.csv`

Additional information about these resources is listed below in Table 1.

Table 1:
| File Name             | Brief Description of Contents |
|-----------------------|-------------------------------|
| `departments.csv`     | Department numbers and names for the Nine (9) departments of Pewlett-Hackard |
| `dept_emp.csv`        | Listing of 331,603 current and former employee numbers (300,024 unique) with associated Department(s) and Date(s) of position |
| `dept_manager.csv`    | Listing of 24 current and former employee numbers of Department Managers with associated Department(s) and Date(s) of position |
| `employees.csv`       | Listing of 300,024 unique current and former employee numbers with Birth Date, First Name, Last Name, Gender, and Hire Date |
| `salaries.csv`        | Listing of 300,024 unique current and former employee numbers with Salary and Date(s) of associated pay |
| `titles.csv`          | Listing of 443,308 current and former employee numbers (300,024 unique) with associated Job Title(s) and Date(s) of position |

## Results

Before moving on to any commentary or analysis deriving from this project, we will present the deliverables requested.

1. The Number of Retiring Employees by Title is shown below in Table 2, and is also available in the project GitHub Repository as `retiring_titles.csv`.

Table 2:
| Title | Count |
|-------|-------|
| Senior Engineer | 29414
| Senior Staff | 28254
| Engineer | 14222
| Staff | 12243
| Technique Leader | 4502
| Assistant Engineer | 1761
| Manager | 2


## Summary
