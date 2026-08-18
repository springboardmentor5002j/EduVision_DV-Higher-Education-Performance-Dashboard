# EduVision_DV “ Higher Education Performance Dashboard

## Project Overview

**EduVision_DV** is a Higher Education Performance Dashboard designed to analyze and visualize global university performance, research activity, student characteristics, and country-level education trends.

The project integrates information from the **QS World University Rankings 2025** and **Times Higher Education (THE) World University Rankings 2016â€“2026** datasets and presents the analysis through an interactive Tableau dashboard suite.

The final solution consists of four interconnected dashboards:

- University Overview
- Research Analytics
- Student Analytics
- Country Comparison

The project transforms university-ranking data into meaningful analytical insights that support university benchmarking, research analysis, student analysis, and international education comparisons.

---

## Project Objectives

- Analyze global university performance.
- Compare universities using ranking and performance indicators.
- Analyze research publications, citations, and research impact.
- Study student population, international student representation, and diversity.
- Examine faculty-to-student relationships.
- Compare education performance across countries and regions.
- Identify higher-education trends over time.
- Provide an interactive and user-friendly Tableau dashboard.
- Support data-driven university and country benchmarking.

---

## Dataset Sources

### QS World University Rankings 2025

The QS World University Rankings 2025 dataset provides university-level ranking and location information used as one of the primary sources for the project.

### Times Higher Education World University Rankings 2016â€“2026

The THE World University Rankings dataset covers the period from **2016 to 2026** and supports longitudinal analysis of university performance, research, students, faculty, internationalization, and other higher-education indicators.

The datasets are integrated into a common analytical structure for dashboard development.

---

## Project Workflow

**Data Collection â†’ Data Cleaning â†’ Data Integration â†’ KPI Development â†’ Performance Analysis â†’ Tableau Visualization â†’ Dashboard Integration â†’ Testing & Validation**

### Data Collection
Global university-ranking datasets are collected from QS and Times Higher Education sources.

### Data Cleaning
The datasets are prepared by removing duplicates, standardizing university and country names, handling missing values, and preparing population, percentage, ranking, and performance fields for analysis.

### Data Integration
The QS and THE datasets are combined using standardized university and country information to create a consolidated higher-education dataset.

### KPI Development
Key indicators are developed to support university, research, student, and country-level analysis.

### Performance Analysis
Selected indicators are normalized and combined into a project-specific Performance Index for comparative analysis.

### Dashboard Development
The final dataset is visualized through four interconnected Tableau dashboards.

### Testing and Validation
Dashboard calculations, rankings, filters, trends, comparisons, and navigation are reviewed to ensure consistent analytical results.

---

# Dashboard 1 â€“ University Overview

The **University Overview** dashboard provides a high-level view of global university performance.

### Key Performance Indicators

- Total Universities
- Total Countries
- Total Regions
- Average Academic Reputation
- Average Overall Score

### Main Visualizations

**Top University Rankings**  
Highlights universities with strong ranking and performance values.

**Global University Distribution**  
Shows the distribution of universities across different regions.

**Employment Outcomes by Universities**  
Compares universities using employment-outcome performance.

**University Performance Trends**  
Shows changes in university performance over the 2016â€“2026 period.

**Institutional Comparison**  
Provides a comparison of universities based on overall performance.

### Purpose

This dashboard provides an overall understanding of university performance, academic reputation, geographical distribution, and institutional outcomes.

---

# Dashboard 2 â€“ Research Analytics

The **Research Analytics** dashboard focuses on research productivity, publications, citations, and research impact.

### Key Performance Indicators

- Total Publications
- Total Citations
- Average Citations
- Average Publications
- Average Research Impact

### Main Visualizations

**Publications Analysis**  
Compares universities based on publication output.

**Citation Performance**  
Compares citation performance across regions.

**Top Research Institutions**  
Highlights institutions with strong research performance.

**Research Productivity Trends**  
Shows changes in research productivity over time.

**Research Impact Comparison**  
Compares research activity using publication and citation-related measures.

### Purpose

This dashboard helps identify research-performing institutions and understand regional and institutional research trends.

---

# Dashboard 3 â€“ Student Analytics

The **Student Analytics** dashboard focuses on student population, internationalization, diversity, enrollment, and faculty relationships.

### Key Performance Indicators

- Total Students
- International Students
- Faculty-to-Student Ratio
- Average Student Diversity
- Total Faculty

### Main Visualizations

**International Student Analysis**  
Compares countries based on international student representation.

**Faculty-to-Student Ratio Analysis**  
Compares universities using faculty and student relationship indicators.

**Enrollment Comparisons**  
Compares universities based on student population.

**Student Diversity Trends**  
Shows changes in student diversity over time.

**Student Distribution Analysis**  
Displays the geographical distribution of students.

### Purpose

This dashboard provides insights into student scale, international student representation, diversity, enrollment, and faculty-student relationships.

---

# Dashboard 4 â€“ Country Comparison

The **Country Comparison** dashboard provides country-level and regional benchmarking.

### Key Performance Indicators

- Total Countries
- Average Overall Score
- Average Global Rank Score
- Average Performance Index
- Total Universities

### Main Visualizations

**Country Ranking Comparison**  
Compares countries based on university-ranking representation.

**Education Performance Benchmarking**  
Compares countries using average performance indicators.

**Regional Education Trends**  
Shows changes in average education performance across regions over time.

**Top Performing Countries**  
Highlights countries with strong average ranking and performance indicators.

### Purpose

This dashboard supports international benchmarking and helps identify high-performing countries and regional education trends.

---

# Key Performance Indicators

| KPI | Purpose |
|---|---|
| Global Rank Score | Represents ranking performance using a project-defined score |
| Research Productivity Index | Represents research quality relative to the available student/faculty-related measure |
| Faculty-to-Student Ratio | Supports analysis of faculty and student relationships |
| International Student Percentage | Measures international student representation |
| Performance Index | Combines selected ranking, research, and internationalization indicators |
| Overall Score | Supports institutional performance comparison |
| Academic Reputation | Supports academic excellence analysis |
| Publications | Measures research output |
| Citations | Measures research influence |
| Research Impact | Supports research-impact comparison |
| Student Population | Measures enrollment scale |
| Student Diversity | Supports analysis of student diversity trends |

---

# Performance Index

The project includes a **Performance Index** as a comparative analytical measure.

The index combines:

- Global Rank Score â€“ **40%**
- Research Productivity Index â€“ **30%**
- International Student Percentage â€“ **30%**

The Performance Index is a **project-specific analytical indicator** created for benchmarking purposes. It should not be interpreted as an official QS or THE ranking score.

---

# Dashboard Filters and Interactivity

The dashboard suite provides interactive analysis through:

- Year filter
- Region filter
- Country filter
- Subject filter
- University comparisons
- Interactive charts
- Geographic maps
- Dashboard navigation
- Cross-dashboard analysis

The dashboards are connected through navigation controls, allowing users to move between University Overview, Research Analytics, Student Analytics, and Country Comparison.

---

# Key Insights Supported by the Dashboard

EduVision_DV enables users to explore:

- Leading universities based on selected performance indicators.
- Distribution of universities across countries and regions.
- Changes in university performance over time.
- Leading research institutions.
- Publication and citation performance.
- Research productivity trends.
- International student representation.
- Student population and enrollment patterns.
- Student diversity trends.
- Faculty-to-student relationships.
- Country-level education performance.
- Regional education trends.
- Top-performing countries.

---

# Target Users

### Students
- Compare universities.
- Explore university performance.
- Understand student diversity and internationalization.

### Researchers
- Analyze publications and citations.
- Compare research performance.
- Explore research productivity and impact.

### University Administrators
- Benchmark institutional performance.
- Analyze student and research indicators.
- Compare institutional outcomes.

### Policymakers and Education Consultants
- Compare countries and regions.
- Identify education-performance trends.
- Support evidence-based higher-education benchmarking.

---

# Project Structure

```text
EduVision_DV/
â”‚
â”œâ”€â”€ data/
â”‚   â”œâ”€â”€ qs-world-rankings-2025.csv
â”‚   â”œâ”€â”€ THE World University Rankings 2016-2026.csv
â”‚   â”œâ”€â”€ university_cleaned.csv
â”‚   â””â”€â”€ university final dataset.csv
â”‚
â”œâ”€â”€ dashboard/
â”‚   â””â”€â”€ EduVision_DV.twbx
â”‚
â”œâ”€â”€ docs/
â”‚   â””â”€â”€ project_documentation
â”‚
â””â”€â”€ README.md
```

---

# Project Deliverables

- Integrated and cleaned university dataset.
- Final Tableau-ready dataset.
- Tableau workbook containing four dashboards.
- Project documentation.
- GitHub project repository.
- Tableau Public deployment, where applicable.

---

# Data Quality and Validation

The project includes validation of:

- Duplicate records.
- Missing values.
- University and country naming consistency.
- Ranking indicators.
- KPI calculations.
- Dashboard filters.
- Dashboard navigation.
- Visual comparisons.
- Geographic analysis.
- Time-series trends.

The project specification targets high dataset completeness, accurate KPI calculations, integrated dashboards, and portfolio-ready documentation.

---

# Technology Stack

| Area | Technology |
|---|---|
| Data Processing | Python |
| Data Analysis | Pandas |
| KPI Development | Python / Statistical Transformation |
| Exploratory Visualization | Plotly |
| Dashboard Development | Tableau Desktop / Tableau Public |
| Dashboard Integration | Tableau Filters, Parameters and Actions |
| Data Storage | CSV / XLSX |
| Documentation | Markdown / GitHub |
| Development Environment | Google Colab |

---

# Future Enhancements

- Incorporating additional ranking datasets.
- Adding automated data refresh.
- Improving university-name matching across data sources.
- Adding more institution-level drill-down analysis.
- Adding year-over-year KPI changes.
- Adding advanced parameter-based comparisons.
- Adding additional research-impact indicators.
- Adding automated data-quality reporting.
- Expanding country and regional benchmarking.
- Publishing the complete dashboard as a portfolio project.

---

# Conclusion

**EduVision_DV â€“ Higher Education Performance Dashboard** provides an integrated analytical view of global higher education.

By combining university-ranking information with research, student, institutional, and geographical indicators, the project enables users to explore university performance from multiple perspectives.

The four-dashboard Tableau suite provides a unified environment for:

- University performance analysis
- Research analytics
- Student analytics
- Country comparison

The project demonstrates an end-to-end higher-education analytics solution focused on university benchmarking, research performance, student analysis, and country-level education comparison.

---

## Author

**J. Manibharathi**

**Project:** EduVision_DV â€“ Higher Education Performance Dashboard

**Focus Areas:** Higher Education Analytics, University Benchmarking, Research Analytics, Student Analytics, and Country Comparison
