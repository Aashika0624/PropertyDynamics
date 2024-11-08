# PropertyDynamics

## Overview

**PropertyDynamics** is a data science project developed for the Statistics for AI and Data Science coursework. The objective is to analyze and predict the average property prices across various regions in England over a 36-month period. By examining different property types—detached, semi-detached, terraced, and flats—this project leverages statistical methods and regression modeling to understand price trends and regional differences, providing insights into the dynamics of the English property market.

## Objectives

- **Analyze Property Price Trends:** Examine how property prices for flats and detached properties have changed over 36 months across 9 regions.
- **Identify Regional Differences:** Determine whether changes in flat prices differ significantly across regions using statistical tests.

## Key Variables

- **Predictors:**
  - **Month:** Date of observation.
  - **Area:** Local government area.
  - **Region:** One of 9 regions in England.
  - **Property Types:** Detached, Semi-detached, Terraced, Flat.

- **Target:**
  - **Average Property Price:** For each property type (Detached, Semi-detached, Terraced, Flat).

## Key Findings

- **Price Trends:**
  - **Detached vs. Flats:** Detached properties consistently have higher average prices than flats across all regions.
  - **London's Market:** London exhibits significantly higher property prices compared to other regions, reflecting its status as a high-demand area.
  - **Stability:** Most regions show stable or slightly increasing property prices over time, indicating a resilient housing market.

- **Regional Differences:**
  - **Chi-Square Test Results:** The chi-square test revealed a significant association between regions and the direction of flat price changes from July 2017 to July 2018 (p-value < 0.001), indicating that flat price changes do not occur uniformly across regions.
  - **Price Changes:** London experienced the most significant decrease in flat prices, while Yorkshire and The Humber saw an increase, highlighting diverse regional property market behaviors.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- SciPy

## Conclusion

The **PropertyDynamics** project underscores the importance of regional factors in the English property market. While detached properties maintain higher price levels consistently, flat prices exhibit significant regional variations. London stands out with its unique market dynamics, experiencing notable price decreases, whereas regions like Yorkshire and The Humber show price increases. The statistical analysis confirms that property price changes are influenced by localized factors, suggesting that future models should incorporate additional regional-specific variables to enhance predictive accuracy. This analysis provides valuable insights for stakeholders aiming to understand and navigate the complexities of the property market across different English regions.
