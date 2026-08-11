# Academic Performance Analysis

An independent, self-directed data analytics project analyzing student academic 
performance across three programs (PCM, PC, PM) using Excel, SQL, and Power BI.

## Overview
- **Dataset:** 1,410 student-subject records across multiple subjects and semesters
- **Tools used:** Excel, MySQL Workbench, Power BI
- **Goal:** Clean raw academic data, calculate performance KPIs, and build an 
  interactive dashboard for stakeholder-style reporting

## Process

**1. Data Cleaning (Excel)**
- Removed 20 duplicate entries and resolved 16 missing-value fields
- Applied VLOOKUP for subject-wise benchmarking and PivotTable analysis

**2. Querying (MySQL)**
- Wrote SQL queries to calculate pass rate, subject-wise averages, and 
  attendance percentage
- Identified 113 at-risk students based on marks and attendance thresholds

**3. Dashboard (Power BI)**
- Built KPI cards for Pass Rate, Total Students, Average Marks, and At-Risk Count
- Designed bar charts for pass/fail breakdown by subject and program
- Added a drill-down table for at-risk student identification
- Included program and year-of-study slicers for interactive filtering

## Key Findings
- Overall pass rate: 73%
- Weakest-performing subjects: Waves and Optics, Mechanics
- 113 students flagged as at-risk based on marks/attendance thresholds

## Files
- `/data` — cleaned dataset (CSV)
- `/sql` — SQL queries with comments
- `/power-bi` — Power BI dashboard file (.pbix)
- `/screenshots` — dashboard preview images

## Dashboard Preview
![dashboard](screenshots/dashboard-overview.png)

---
*This is a self-directed learning project built on a synthetic academic dataset, 
independent of any employer data.*
