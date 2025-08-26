# Exploring Descriptive and Inferential Statistics using Python for Data-Driven Decision-Making

**Author:** Mohomed Shaveen Hassim  
**Supervisor:** Dr. Swathi Ganesan  
**Institution:** York St John University — MSc Data Science  
**Date:** September 2024 - September 2025

---

## Summary
This repository contains materials, code and the dissertation PDF for the MSc research titled _"Exploring Descriptive and Inferential Statistics using Python for Data-Driven Decision-Making"_. The study applies descriptive and inferential statistical techniques (Shapiro-Wilk, t-test, ANOVA, regression) to the Online Retail dataset to extract business insights on customer behaviour, pricing and purchase patterns.

---

## Contents
- `docs/` — dissertation PDF and supporting documents.
- `notebooks/` — Jupyter notebooks used for analysis:
  - `Research.ipynb`
- `src/` — reusable Python scripts for preprocessing, plotting, and tests.
- `data/` — data handling instructions.
- `figures/` — key output figures.
- `requirements.txt` — required Python packages.

---

## Key Analyses & Statistical Tests  
- **Data Cleaning & Preprocessing**  
  - Removal of missing values, duplicates, and outliers  
  - Conversion of data types for consistency  
- **Descriptive Statistics**  
  - Central tendency, dispersion, and distribution analysis of key variables (Quantity, UnitPrice)  
- **Hypothesis Testing**  
  - *Shapiro-Wilk Test* — tested normality of sales data  
  - *t-Test* — compared mean unit prices between UK and Germany  
  - *ANOVA* — examined differences in mean quantities sold across multiple countries  
- **Regression Analysis**  
  - Linear regression to evaluate the relationship between price and quantity sold  
- **Visualization**  
  - Histograms, boxplots, heatmaps, and comparative plots to support statistical findings  

---

## Methodology  
1. **Data Collection & Cleaning** — Prepared the Online Retail dataset by filtering invalid records and correcting formats.  
2. **Exploratory Data Analysis (EDA)** — Generated descriptive summaries and visualized sales behaviour.  
3. **Inferential Statistics** — Applied hypothesis tests and regression to validate patterns and relationships.  
4. **Business Interpretation** — Linked statistical outcomes to actionable insights for pricing, inventory, and strategy.  

---

## Insights  
- 📊 **Non-Normal Distribution**: Both quantity and unit price showed skewness, highlighting the importance of using appropriate statistical methods.  
- 💷 **Pricing Consistency**: No significant mean price difference between UK and Germany, suggesting standardized pricing across these markets.  
- 🌍 **Regional Differences**: ANOVA confirmed significant variations in quantities sold between countries, informing localized sales strategies.  
- 📉 **Weak Price-Quantity Correlation**: Regression showed only a limited relationship between price and purchase volume, indicating other factors drive demand.  
- 🏢 **Business Value**: Findings demonstrate how statistical testing supports **evidence-based decision-making** in e-commerce.  

---
