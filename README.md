# EU/EEA COVID-19 Data Analysis

This project performs a statistical analysis of daily COVID-19 case and death data across 30 European Union (EU) and European Economic Area (EEA) countries using R.

The goal was to explore incidence and fatality trends over time, compare country-level outcomes, and build a predictive model for total cases based on population and economic factors.

---

## Key Insights

- Daily incidence rates surged dramatically during the Omicron wave in late 2021 and early 2022 across all countries
- Romania showed significantly different mean daily incidence rates compared to Portugal, reflecting disparities in healthcare capacity and vaccination rollout
- Fatality rates declined relative to case counts in later waves, consistent with widespread vaccination across the EU/EEA
- Population is the strongest predictor of total COVID-19 cases; GDP per capita and population density add limited predictive value at the country level

---

## Tools Used

- R
- ggplot2
- dplyr
- tidyverse
- lubridate
- zoo
- R Markdown

---

## Project Objectives

- Compute daily incidence and fatality rates per 100K individuals for each country
- Visualize COVID-19 trends across the full dataset time frame
- Conduct a Welch's two-sample t-test comparing Romania and Portugal
- Assess correlation between incidence and fatality rates using Spearman's method
- Fit and evaluate a linear regression model predicting total cases from population, population density, and GDP per capita

---

## Files in This Repository

- `covid19-eu-analysis.Rmd` — Full R Markdown source with code and written analysis
- `covid19-eu-analysis.html` — Knitted output with all visualizations and results

---

## What I Learned

- Applying hypothesis testing and correlation analysis to real-world epidemiological data
- Handling time series data with rolling averages to reduce reporting noise
- Evaluating full vs. reduced regression models using adjusted R-squared
- Communicating statistical findings clearly in a reproducible R Markdown report
