# gender-discrimination-analysis
This project analyzes the relationship between **gender, education, experience, and seniority** on **beginning salaries** using data from a linear regression framework. The goal is to explore whether salary differences can be explained by these factors or if evidence of a gender-based salary gap remains after controlling for them. The source of the data is from robackdata::banksalary.

---

## Overview
The analysis is performed in **R** using **Quarto** for reproducible reporting.  
It includes:
- **Data Import & Preparation**
- **Exploratory Data Analysis (EDA)** with visualizations
- **Multiple Linear Regression Models**
- **Model Diagnostics** (checking LINE assumptions)
- **Log-transformed regression model** for percentage-based interpretation

---

## Libraries Used
This project primarily uses the **tidyverse** collection of packages, especially:
- **`dplyr`**
- **`ggplot2`**
Other base R functions are used for modeling (`lm()`, `anova()`, `summary()`).

---

## Key Findings
- Education, experience, and seniority are all statistically significant predictors of beginning salary.  
- After controlling for these factors, **sex remains a significant variable**, suggesting a gender-based salary difference.  
- The log-transformed model shows that men earn approximately **13–14% more** than women, on average.

---
