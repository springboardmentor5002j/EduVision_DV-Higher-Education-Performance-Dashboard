# EduVision DV – Project Documentation

## 1. Project Overview

EduVision DV (Higher Education Performance Dashboard) is a higher education analytics project developed to analyze university rankings, research performance, student diversity, academic excellence, and global education trends.

The project uses publicly available university ranking datasets, including QS World University Rankings and Times Higher Education World University Rankings. The raw educational data is processed and transformed into Tableau-ready datasets for interactive analysis.

The final solution consists of four interconnected dashboards:

1. University Overview
2. Research Analytics
3. Student Analytics
4. Country Comparison

---

## 2. Project Objectives

The main objectives of the project are:

- Analyze global university rankings and performance.
- Compare universities across different regions.
- Analyze research publications and citation performance.
- Study international student distribution and student diversity.
- Analyze faculty-to-student ratios.
- Compare country-level education performance.
- Identify trends and patterns in higher education.
- Develop interactive Tableau dashboards for educational analytics.

---

## 3. Data Processing Workflow

The project follows the workflow below:

Data Collection
↓
Data Cleaning & Transformation
↓
KPI Engineering
↓
Dashboard Development
↓
Dashboard Integration
↓
Testing & Validation
↓
Documentation & Delivery

### Data Collection

The project integrates university ranking datasets from QS World University Rankings and Times Higher Education World University Rankings.

### Data Cleaning

The preprocessing workflow includes:

- Removing duplicate records.
- Standardizing university names.
- Standardizing country names.
- Cleaning numerical and percentage-based fields.
- Handling missing values.
- Preparing a final dataset for Tableau visualization.

### Feature Engineering

Additional analytical fields were created to support dashboard development, including:

- Global Rank Score
- Research Productivity Index
- Faculty-to-Student Ratio
- International Student Percentage
- Student Diversity
- Publications
- Citations
- Country
- Region
- Performance Index

---

## 4. Key Performance Indicators

### Global Ranking Score

A score derived from university ranking information to support comparison of global university performance.

### Research Productivity Index

The project calculates a research productivity measure using research quality and the student-to-staff ratio.

### Faculty-to-Student Ratio

This KPI represents the faculty/student relationship and is used to compare faculty availability across universities.

### International Student Percentage

This KPI represents the proportion of international students and is used to analyze student diversity.

### Student Diversity

Student diversity is represented using international student percentage data and is visualized across different years and regions.

### Performance Index

A combined analytical index created using weighted components of:

- Global Rank Score – 40%
- Research Productivity Index – 30%
- International Student Percentage – 30%

---

## 5. Dashboard Modules

### 5.1 University Overview

The University Overview dashboard provides a high-level view of global higher education performance.

It includes:

- Total Countries
- Average Global Rank Score
- Total Universities
- Universities by Region
- Top 10 Universities

### 5.2 Research Analytics

The Research Analytics dashboard focuses on research performance.

It includes:

- Publications vs Citations analysis
- Research performance comparison
- Research productivity analysis
- Faculty-to-student ratio
- Top research-performing universities

### 5.3 Student Analytics

The Student Analytics dashboard focuses on student diversity and international education.

It includes:

- International Students by Region
- Student Diversity Trend
- Year-based analysis
- Region filters
- Subject filters

### 5.4 Country Comparison

The Country Comparison dashboard compares higher education performance across countries.

It includes:

- Country Ranking Comparison
- Top-performing countries
- Global university performance map
- Country-level benchmarking

---

## 6. Dashboard Interactivity

The Tableau workbook uses interactive features such as:

- Filters
- Dashboard actions
- Navigation controls
- Year selection
- Region selection
- Subject selection
- Cross-dashboard filtering

These features allow users to explore university and country-level performance interactively.

---

## 7. Technology Stack

| Area | Tools |
|---|---|
| Data Collection | Python, QS Rankings, World University Rankings |
| Data Processing | Pandas, NumPy |
| Data Cleaning | Python |
| Data Visualization | Tableau Desktop / Tableau Public |
| Dashboard Integration | Tableau Filters, Parameters, Actions |
| Documentation | Markdown, GitHub |

---

## 8. Repository Structure

```text
EduVision_DV-Higher-Education-Performance-Dashboard/
│
├── scripts/
│   ├── 01_Data_Preprocessing_and_Feature_Engineering.ipynb
│   └── 02_Final_Data_Cleaning.ipynb
│
├── Data/
│   └── cleaned_dataset_with_subject.csv
│
├── dashboard/
│   └── Global University Performance Analytics Dashboard.twbx
│
├── docs/
│   └── Project_Documentation.md
│
└── README.md
