# BCG-Vaccination-Coverage-and-Child-Mortality-in-Nigeria-1980-2023-

OVERVIEW

This project explores how BCG vaccination coverage relates to child mortality trends in Nigeria over time.
The goal is to understand whether increased vaccination rates are associated with reductions in child mortality.

OBJECTIVES

-To explore trends in BCG vaccination coverage and child mortality in Nigeria.

-To examine the statistical relationship between vaccination coverage and child mortality.

-To use regression analysis to estimate how much vaccination coverage impacts child mortality.

DATA SOURCES

-BCG Vaccination Coverage: UNICEF Data (https://data.unicef.org/wp-content/uploads/2024/07/wuenic2024rev_web-update.xlsx)

-Child Mortality Rate: Our World in Data (https://ourworldindata.org/grapher/child-mortality?overlay=download-data)

DATA PREPARATION

-Converted wide format to long format to align years properly.

-Merged both datasets on Year for direct comparison.

-Cleaned missing values and ensured numeric consistency.

-Created a smoothed column for child mortality using a rolling mean for better trend visualization.

EXPLORATORY ANALYSIS

-Visualized trends using a twin-axis plot to compare vaccination and mortality rates.

-Observed a steady rise in vaccination coverage over the decades, while child mortality dropped sharply, indicating a potential inverse relationship.

📈 STATISTICAL ANALYSIS

-Pearson Correlation:

     r = -0.613, p-value = 0.00001
Which means there is a  strong negative correlation, as vaccination coverage increases, child mortality decreases.

-Linear Regression Model:

      R² = 0.376 
which means about 38% of changes in mortality can be explained by vaccination coverage.

The slope (-0.1458) means that for every 1% increase in vaccination, the child mortality rate decreases by 0.15 deaths on average.

Key Insights

There’s a statistically significant inverse relationship between BCG vaccination coverage and child mortality in Nigeria.

While vaccination is a strong factor, the R² value suggests that other health and socioeconomic factors also influence child survival.

Continuous vaccination programs remain vital for reducing preventable deaths.

🪄 Tools & Libraries

Python (Pandas, Matplotlib, Seaborn, Statsmodels, Scipy)

Data Visualization – Line charts, twin-axis plots

Statistical Methods – Correlation and linear regression

🗣️ Conclusion

The data shows a clear message — higher vaccination coverage saves children’s lives.
Even though vaccines alone don’t explain everything, they remain a cornerstone of child health progress in Nigeria.
