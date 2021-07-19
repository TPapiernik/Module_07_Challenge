# Module 07 Challenge - Pewlett-Hackard Analysis - SQL

## Overview

In the coming years, many employees will be eligible for retirement at Pewlett-Hackard.

In order to better prepare as a company for this eventuality, Bobby and I were tasked
with compiling a set of summary data and an executive report about Pewlett-Hackard's
aging workforce.

### Deliverables:
1. The Number of Retiring Employees by Title
2. The Employees Eligible for the Mentorship Program
3. This written report

### Criteria:
As of July 18, 2021, employees currently eligible or soon to be eligible for retirement are those that: Were born between January 1, 1952 and December 31, 1955 (Ages 66-69).

Employees eligible for the Mentorship Program are those that: Were born between January 1, 1965 and December 31, 1965 (Ages 56).

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

**Table 1:**
| File Name             | Brief Description of Contents |
|-----------------------|-------------------------------|
| `departments.csv`     | Department numbers and names for the Nine (9) departments of Pewlett-Hackard |
| `dept_emp.csv`        | Listing of 331,603 current and former employee numbers (300,024 unique) with associated Department(s) and Date(s) of position |
| `dept_manager.csv`    | Listing of 24 current and former employee numbers of Department Managers with associated Department(s) and Date(s) of position |
| `employees.csv`       | Listing of 300,024 unique current and former employee numbers with Birth Date, First Name, Last Name, Gender, and Hire Date |
| `salaries.csv`        | Listing of 300,024 unique current and former employee numbers with Salary and Date(s) of associated pay |
| `titles.csv`          | Listing of 443,308 current and former employee numbers (300,024 unique) with associated Job Title(s) and Date(s) of position |

## Results

### Deliverables

Before moving on to commentary and analysis, we will present the deliverables requested.


1. The Number of Retiring Employees by Title is shown below in Table 2, and is also available in the project GitHub Repository under `Data/retiring_titles.csv`.

**Table 2:**
| Title | Count |
|-------|-------|
| Senior Engineer | 29414
| Senior Staff | 28254
| Engineer | 14222
| Staff | 12243
| Technique Leader | 4502
| Assistant Engineer | 1761
| Manager | 2

Additionally, the Current Job Titles for all 90,398 employees currently eligible for retirement can be viewed in the project GitHub Repository under `Data/unique_titles.csv`. Complete information on each employee including all of their current and former job titles and position date(s) is under `Data/retirement_titles.csv`

2. The Employees Eligible for the Mentorship Program. There are a total of 1,549 current employees who are eligible for the mentorship program.
In order to conserve space, the entire table will not be reproduced here, but it is available in the project GitHub Repository under `Data/mentorship_eligibility.csv`.

### Commentary on Deliverables

While exploring the data provided, and the relationships between them, we noticed a few things that were slightly out of the scope of our directive, but are definitely worth noting.

1. Taking a look at just the Salaries Table, it would appear that either no employee has received a raise since January 31, 2001 at the latest, or else the original salaries data source has become corrupted, has not been updated, or there was some other error in data retrieval. A quick screen capture of what this looks like is shown here in Figure 1:

**Figure 1:**
![Figure 1](Resources/Figure1.png "Figure 1")

2.
3.
4.


## Summary
