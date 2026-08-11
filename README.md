Academic Performance Analysis

An independent, self-directed data analytics project analyzing student academic performance across three programs (PCM, PC, PM) using Excel, SQL, and Power BI.

Overview
Dataset: 1,410 student-subject records across multiple subjects and semesters
Tools used: Excel, MySQL Workbench, Power BI
Goal: Clean raw academic data, calculate performance KPIs, and build an interactive dashboard for stakeholder-style reporting
Process

1. Data Cleaning (Excel)

Removed 20 duplicate entries and resolved 16 missing-value fields
Applied VLOOKUP for subject-wise benchmarking and PivotTable analysis

2. Querying (MySQL)

Wrote SQL queries to calculate pass rate, subject-wise averages, and attendance percentage
Identified at-risk students based on marks and attendance thresholds

3. Dashboard (Power BI)

Built KPI cards for Pass Rate, Total Students, Average Marks, and At-Risk Count
Designed bar charts for pass/fail breakdown by subject and program
Added a drill-down table for at-risk student identification
Included program and year-of-study slicers for interactive filtering
Key Findings
Overall pass rate: 73%
Weakest-performing subjects: Waves and Optics, Mechanics
Students flagged as at-risk based on marks/attendance thresholds
Files in this Repository
physics_even_semester_performance.csv — cleaned dataset (CSV format)
physics_even_semester_performance.xls — cleaned dataset (Excel format)
sql queries.txt — SQL queries used for KPI calculations and at-risk analysis
student performance.pbix — Power BI dashboard file
Dashboard overview.png — dashboard preview screenshot
