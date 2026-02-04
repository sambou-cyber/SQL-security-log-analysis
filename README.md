# SQL Security Log Analysis (AND, OR, NOT Filters)

# Project Overview
This project demonstrates how SQL can be used to investigate potential security incidents by analyzing employee data and login activity. Using structured queries with `AND`, `OR`, `NOT`, `LIKE`, date, and time filters, I examined authentication logs and employee records to identify suspicious behavior and support security operations.

The analysis focuses on failed login attempts, after-hours access, geographic anomalies, and identifying specific employee groups for security updates.

## Scenario
  I investigated potential security issues involving:
- Failed login attempts after business hours
- Login activity on suspicious dates
- Login attempts originating outside of Mexico
- Employees in specific departments requiring system updates

The data was queried from the following tables:
- `log_in_attempts`
- `employees`
- `machines`

## Key Skills Demonstrated
- SQL filtering with `AND`, `OR`, and `NOT`
- Pattern matching using `LIKE`
- Date and time-based filtering
- Investigating authentication logs
- Identifying high-risk access patterns
- Security-focused data analysis

## Examples of Queries Used
- After-hours failed login attempts
- Login activity on specific dates
- Login attempts outside a geographic region
- Employees in Marketing (East building)
- Employees in Finance or Sales
- Employees not in the IT department

> Screenshots of executed SQL queries and results are embedded in the accompanying PDF report.

## Files in This Repository
- `sql-security-log-analysis_report.pdf` — Full report with queries, screenshots, and explanations
- `README.md` — Project overview and context


This project reflects real-world investigative techniques used to detect unauthorized access, policy violations, and potential security incidents.

## Tools Used
- MariaDB / SQL
- Linux command-line environment
Prepared by: Sambou Kamissoko 
LinkedIn: https://www.linkedin.com/in/sambouk/
