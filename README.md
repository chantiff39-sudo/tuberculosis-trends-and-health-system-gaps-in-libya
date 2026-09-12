# Tuberculosis Trends and Health-System Gaps in Libya

## Project Overview

This public-health data analysis examines changes in tuberculosis incidence, mortality, case reporting, and estimated case detection in Libya. It combines WHO tuberculosis indicators with annual migration estimates compiled from official IOM Displacement Tracking Matrix reports.

The main analysis covers 2000–2024. Comparisons involving migration use the overlapping 2017–2024 period.

## Research Question

How has the tuberculosis burden in Libya changed over time, and how might migration, displacement, conflict, and health-system limitations relate to the observed trends?

## Key Findings

- Estimated TB incidence increased from 40 cases per 100,000 population in 2019 to 63 in 2024.
- Estimated TB mortality increased from 4.3 deaths per 100,000 population in 2019 to 13.0 in 2024.
- Reported TB cases increased more slowly than WHO-estimated incident cases.
- The estimated case-detection gap widened from 585 cases in 2019 to 1,988 cases in 2024.
- WHO’s estimated case detection rate declined from 80% in 2019 to 58% in 2024.
- TB incidence and IOM migrant estimates increased during an overlapping period, but this ecological analysis cannot establish causation.

## Data Sources

- WHO Global Tuberculosis Programme
- WHO Global Tuberculosis Database
- IOM Displacement Tracking Matrix Libya migrant reports

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Kaggle Notebooks

## Methods

- Data cleaning and validation
- Dataset merging
- Missing-data assessment
- Descriptive trend analysis
- Derived case-detection indicators
- Pearson and Spearman correlation
- Indexed trend comparison
- Visualization of WHO uncertainty bounds

## Important Limitation

The migration comparison contains only eight overlapping annual observations. The correlations are exploratory, may reflect shared time trends and confounding, and do not demonstrate that migration caused changes in tuberculosis incidence.

## Repository Files

- `libya-tb-trends-and-health-system-gaps.ipynb` — complete analysis notebook
- `libya_tb_clean_2000_2024.csv` — cleaned annual TB indicators
- `libya_iom_migration_2017_2024.csv` — compiled annual IOM migration estimates
- `libya_tb_migration_merged_2017_2024.csv` — merged analytical dataset

## Author

Haleemah Alramli  
MSc Molecular Medicine researcher interested in public health, epidemiology, data analysis, and health research.
