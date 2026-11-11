# SQL HR Database Analysis (MySQL)

SQL queries written for a Business Workforce Analytics assessment (Module 2) on the `Data_Analytics_HR` database. The document includes each query and a screenshot of its output.

## Database
| Table | Columns |
|---|---|
| `employees` | emp_id, emp_name, gender, age, dept_id, job_role, salary, city, email |
| `departments` | dept_id, dept_name |

The sample data has 15 employees across 5 departments (HR, Finance, IT, Sales, Marketing).

## What's Covered
| Section | Topics |
|---|---|
| Q1: Find the Right Employees | Filtering, `ORDER BY`, `IN`, `LIKE`, `LIMIT` |
| Q2: Understand the Workforce | `GROUP BY`, `HAVING`, aggregate functions, `CASE` salary bands |
| Q3: Connect & Investigate | Joins, subqueries, department payroll |
| Q4: Validate & Recommend | `IS NULL` checks, `LEFT JOIN` for unmatched records |

## Results from the Sample Data
- IT is the largest department: 5 employees, average salary 82,200, payroll 411,000
- Finance has 3 employees (average 74,667); HR, Sales and Marketing have 2 each
- Data checks found 1 employee with no email and 1 employee with no department

## Skills
SQL · MySQL · Joins · Aggregation · Subqueries · CASE · Data validation
