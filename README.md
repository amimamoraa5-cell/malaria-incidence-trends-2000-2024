# Malaria Incidence Trends Across 97 Countries, 2000–2024

### A Cross-Country Statistical Analysis of Regional and Socioeconomic Differences

## Project Overview

This research investigates malaria incidence trends across 97 countries from 2000 to 2024 using World Bank World Development Indicators (WDI) data.

The study examines changes in malaria incidence over time and explores differences across geographic regions and income groups. Python was used for data cleaning, exploratory analysis, statistical testing, and visualization.

## Research Objectives

- Examine malaria incidence trends between 2000 and 2024.
- Compare malaria incidence across geographic regions.
- Investigate differences in malaria incidence across income groups.
- Apply statistical methods to evaluate temporal trends and group differences.
- Identify patterns that may inform further public health research.

## Data Source

**World Bank — World Development Indicators**

- Indicator: Incidence of malaria (per 1,000 population at risk)
- Indicator code: `SH.MLR.INCD.P3`
- Study period: 2000–2024
- Final analytical sample: 97 countries with complete observations for all 25 years.

The dataset was prepared by combining malaria incidence data with country metadata, including geographic region and income classification.

## Methodology

The analysis involved:

1. Data acquisition and preparation.
2. Country metadata integration.
3. Missing-data assessment and complete-case selection.
4. Descriptive statistical analysis.
5. Annual trend analysis.
6. Linear regression to examine temporal trends.
7. Regional comparisons.
8. Income-group comparisons.
9. Non-parametric statistical testing.

### Tools

- Python
- pandas
- NumPy
- Matplotlib
- SciPy
- Kaggle Notebooks
- GitHub

## Key Findings

### Overall Trend

The mean malaria incidence across the 97-country sample declined from approximately 154.50 in 2000 to 90.47 in 2024.

This represents an approximate 41.44% reduction over the study period.

Linear regression indicated a statistically significant downward trend:

- Slope: −2.8377
- R-squared: 0.8762
- P-value: 6.46 × 10⁻¹²

### Regional Differences

Sub-Saharan Africa recorded the highest average malaria incidence among the regions included in the analysis.

The regional mean incidence values varied substantially, highlighting geographic differences in malaria burden.

### Income-Group Differences

Malaria incidence also differed across country income groups.

The Kruskal–Wallis test indicated a statistically significant difference in incidence distributions across income groups:

- H-statistic: 37.3008
- P-value: 3.97 × 10⁻⁸

These findings indicate an overall difference among income groups. They do not independently establish which specific groups differ from one another.

## Limitations

- The analysis includes 97 countries with complete observations, rather than all countries worldwide.
- Complete-case selection may introduce selection bias.
- Regional and income-group sample sizes are unequal.
- Some groups contain very few countries, limiting the strength of comparisons.
- Country-level averages are not population-weighted global estimates.
- The analysis identifies statistical associations and trends but does not establish causal relationships.
- Malaria incidence estimates may be affected by differences in surveillance and reporting.

## Conclusion

The analysis identifies a substantial decline in mean malaria incidence across the selected countries between 2000 and 2024.

However, regional and socioeconomic differences remain evident. The findings emphasize the importance of examining malaria trends across different geographic and economic contexts rather than relying only on overall averages.

This project demonstrates the application of Python-based data analysis, statistical testing, and visualization to a public health research question.

## Author

**Amima Moraa**

Independent Data Analysis Research Project

## Project Status

Research analysis completed. Project documentation and GitHub organization in progress.
