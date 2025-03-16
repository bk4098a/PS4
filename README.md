# Problem Set 4: COVID-19, Mask Use, and Vaccination Report

**Course:** SIS-750: Data Analysis (Spring 2025)  
**Author:** Byeolha Kim  
**Due Date:** March 23, 2025  

## 📌 Overview

This repository contains the completed analysis and report for Problem Set 4, which examines how COVID-19 outcomes across U.S. counties were influenced by mask-wearing and vaccination rates in 2022.

The project was completed using R Markdown and includes data preprocessing, visualization, and regression analysis based on the code provided by the data team. The final output is a professionally formatted PDF report.

---

## 📁 Repository Contents

- `PS4.Rmd`: R Markdown source file for the full report (code included in appendix).
- `PS4.pdf`: Final rendered report in PDF format.
- `cdc vax mar1.csv`: County-level CDC vaccination data used in the analysis.
- `README.md`: This file — summary and documentation.
- `.gitignore`: Standard file to exclude temporary RStudio/LaTeX files.

---

## 📊 Summary of Report Structure

1. **Summary:**  
   Overview of the report's purpose and key findings.

2. **Data:**  
   - Data sources: NYTimes COVID data, CDC vaccination data, NYT mask survey.  
   - Descriptive statistics and visualizations for:
     - COVID-19 death counts
     - Mask usage (% always masking)
     - Vaccination rates

3. **Analysis:**  
   Regression models estimating the effect of mask usage and vaccination on scaled COVID-19 death rates (per 100,000 people), using `felm()` and presented with `gt` tables.

4. **Appendix:**  
   Full R code used for data processing and model estimation.

---

## 📂 Data Sources

- [NYTimes COVID-19 Data](https://github.com/nytimes/covid-19-data)  
- [CDC Vaccination Data](https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-County/8xkx-amqh/data)  
- NYT Mask Use Survey (July 2020)

---

## 🔧 Technical Notes

- All code chunks in the main report body are hidden (`echo = FALSE`) to focus on output and interpretation.
- Full code is included in the Appendix for reproducibility.
- Report was knit using R Markdown with `gt` tables for optimal formatting.

---

## 📎 Instructions to Reproduce

1. Open `PS4.Rmd` in RStudio.
2. Make sure the local file path for `cdc vax mar1.csv` is correct.
3. Knit to PDF.

---
