# Unemployment Analysis with Python

## Project Overview

This project analyzes unemployment trends in India using Python. The analysis focuses on unemployment rates during 2020 and studies how the COVID-19 lockdown period affected employment.

This project was completed as part of the Oasis Infobyte Internship Program (OIBSIP).

## Objective

The objective is to understand unemployment trends using exploratory data analysis and visualization.

The analysis checks:

- State-wise unemployment rates
- Monthly unemployment trend
- COVID-19 impact on unemployment
- Highest and lowest unemployment states
- Relationship between numerical columns

## Dataset Information

Main dataset used:

```text
Unemployment.csv
```

The dataset contains unemployment information for Indian states in 2020.

## Column Details

| Column | Meaning |
| --- | --- |
| Region | Name of the Indian state or union territory |
| Date | Month of the unemployment record |
| Frequency | Data frequency, monthly in this dataset |
| Estimated Unemployment Rate (%) | Percentage of unemployed people in the labour force |
| Estimated Employed | Estimated number of employed people |
| Estimated Labour Participation Rate (%) | Percentage of people participating in the labour force |
| Zone | Region zone such as North, South, East, West, or Northeast |
| longitude | Longitude of the state |
| latitude | Latitude of the state |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Workflow

1. Loaded the dataset.
2. Cleaned column names.
3. Converted the date column into proper date format.
4. Checked missing values and duplicate records.
5. Studied unemployment rate distribution.
6. Analyzed state-wise unemployment rates.
7. Compared unemployment before, during, and after lockdown months.
8. Created visualizations.
9. Wrote key findings and conclusion.

## Analysis Performed

- Dataset overview
- Missing values analysis
- Duplicate records check
- Data type correction
- Outlier check
- State-wise unemployment analysis
- Monthly unemployment trend analysis
- COVID-19 impact analysis
- Correlation analysis
- Top 10 highest unemployment states
- Top 10 lowest unemployment states

## Visualizations

The following screenshots are available in the `screenshots` folder:

- `01_dataset_overview.png`
- `02_missing_values.png`
- `03_unemployment_distribution.png`
- `04_state_wise_unemployment.png`
- `05_monthly_trend.png`
- `06_covid_impact.png`
- `07_correlation_heatmap.png`
- `08_top_10_highest.png`
- `09_top_10_lowest.png`
- `10_zone_wise_unemployment.png`
- `11_outlier_check.png`

## Key Findings

- The average unemployment rate in the dataset is around 12.24%.
- Unemployment increased sharply during April and May 2020.
- The average unemployment rate before lockdown was around 9.76%.
- During the lockdown impact period, the average unemployment rate increased to around 22.75%.
- After the lockdown months, the unemployment rate reduced again to around 9.56%.
- Haryana, Tripura, Jharkhand, Bihar, and Delhi had some of the highest average unemployment rates.
- Meghalaya, Assam, Gujarat, Odisha, and Telangana had some of the lowest average unemployment rates.

## Conclusion

The analysis shows that COVID-19 had a strong short-term impact on unemployment in India. April and May 2020 had the highest unemployment rates, showing the effect of lockdown restrictions. After these months, the unemployment rate started reducing again.

## Internship Reference

This project was completed as part of the Oasis Infobyte Internship Program (OIBSIP), Data Science domain.

## Author

Sumeet Kailash Chauhan
