# EduVision DV – Higher Education Performance Dashboard

## 1. Project Overview

EduVision DV is a higher education analytics project developed to analyze university rankings, research performance, student diversity, academic excellence, and global education trends.

The project uses publicly available university ranking datasets, including QS World University Rankings and Times Higher Education World University Rankings. The raw data is processed and transformed using Python and visualized through interactive Tableau dashboards.

The final dashboard suite consists of four interconnected dashboards:

- University Overview
- Research Analytics
- Student Analytics
- Country Comparison

## 2. Project Objectives

The main objectives of the project are:

- Analyze global university rankings and performance.
- Compare universities across different regions.
- Analyze research publications and citation performance.
- Study international student distribution and diversity.
- Analyze faculty-to-student ratios.
- Compare country-level higher education performance.
- Identify trends in global higher education.
- Develop interactive Tableau dashboards for educational analytics.

## 3. Data Processing

### Data Collection

The project integrates university ranking datasets from:

- QS World University Rankings
- Times Higher Education World University Rankings

### Data Cleaning

The preprocessing workflow includes:

- Removing duplicate records.
- Checking missing values.
- Standardizing university names.
- Standardizing country names.
- Cleaning student population values.
- Cleaning international student percentage values.
- Handling missing values.
- Preparing Tableau-ready datasets.

### Data Integration

The QS and Times Higher Education datasets were merged using standardized university and country information to create a common analytical dataset.

## 4. KPI Engineering

The project includes the following analytical metrics:

### Global Ranking Score

A score derived from university ranking information to support comparison of university performance.

### Research Productivity Index

A research performance metric calculated using research quality and student-to-staff ratio.

### Faculty-to-Student Ratio

Used to analyze the relationship between faculty and students across universities.

### International Student Percentage

Represents the percentage of international students and is used to analyze student diversity.

### Student Diversity

Student diversity is represented using international student percentage data.

### Performance Index

The project calculates a combined Performance Index using:

- Global Rank Score – 40%
- Research Productivity Index – 30%
- International Student Percentage – 30%

## 5. Dashboard Guide

### 5.1 University Overview

The University Overview dashboard provides a high-level view of global university performance.

It includes:

- Total Countries
- Average Global Rank Score
- Total Universities
- Universities by Region
- Top 10 Universities

### 5.2 Research Analytics

The Research Analytics dashboard focuses on university research performance.

It includes:

- Publications analysis
- Citations analysis
- Research productivity
- Research performance comparison
- Faculty-to-student ratio

### 5.3 Student Analytics

The Student Analytics dashboard focuses on student diversity and international education.

It includes:

- International students by region
- Student diversity trends
- Year-wise analysis
- Regional comparisons
- Subject-based analysis

### 5.4 Country Comparison

The Country Comparison dashboard provides country-level higher education analysis.

It includes:

- Country performance comparison
- Education performance benchmarking
- Regional trends
- Top-performing countries
- Global university performance map

## 6. Dashboard Interactivity

The Tableau dashboard suite includes interactive features such as:

- Filters
- Dashboard actions
- Navigation controls
- Year-based analysis
- Region-based analysis
- Subject-based analysis
- University comparisons
- Country-level map visualization

## 7. Project Workflow

```text
Data Collection
      ↓
Data Cleaning & Transformation
      ↓
KPI Engineering
      ↓
Dashboard Planning
      ↓
Dashboard Development
      ↓
Dashboard Integration
      ↓
Testing & Validation
      ↓
Documentation & Delivery
```

## 8. Technology Stack

| Area | Tools |
|---|---|
| Data Collection | Python, QS Rankings, World University Rankings |
| Data Processing | Pandas |
| Data Cleaning | Python |
| Visualization | Tableau Desktop / Tableau Public |
| Dashboard Integration | Tableau Filters, Parameters, Actions |
| Documentation | Markdown, GitHub |

## 9. Testing and Validation

The project includes validation of:

- KPI calculations
- Ranking calculations
- Dashboard interactions
- Educational metrics
- Filters
- Navigation controls
- Dashboard actions

The final Tableau workbook was tested to ensure that the four dashboards are integrated and interactive.

## 10. Final Deliverables

The project deliverables include:

- Python preprocessing notebooks
- Cleaned dataset
- Tableau packaged workbook
- Four integrated Tableau dashboards
- Project documentation
- GitHub repository

## 11. Tableau Public Dashboard

[View the Interactive Tableau Dashboard](https://public.tableau.com/app/profile/santhosh.prabhu5520/viz/GlobalUniversityPerformanceAnalyticsDashboard/Story1)
