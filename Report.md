# Analysis of Income, Health, and Life Expectancy

## Introduction

This report provides a concise analysis of the relationships between income, health expenditure, and life expectancy across different countries. It explores how these variables are interrelated and presents key findings from both a correlation heatmap and a regression analysis.

## Key Observations from the Correlation Heatmap

The correlation heatmap provided insights into the relationships between multiple variables:

- **Income and Life Expectancy**: There is a strong positive correlation (0.61) between income and life expectancy, indicating that countries with higher incomes tend to have longer life expectancies.
- **Child Mortality and Life Expectancy**: A very strong negative correlation (-0.89) exists between child mortality and life expectancy, showing that lower child mortality rates are associated with higher life expectancy.
- **Health Expenditure and Life Expectancy**: The moderate positive correlation (0.54) between health expenditure and life expectancy suggests that higher investment in healthcare generally leads to longer life expectancy.

## Regression Analysis

An Ordinary Least Squares (OLS) regression was performed to further analyze the impact of income, health expenditure, and inflation on life expectancy:

- **Income**: A positive coefficient (0.0003) suggests that as income rises, life expectancy increases. This relationship is statistically significant.
- **Health Expenditure**: The coefficient of 0.333 implies a positive but less significant effect of health expenditure on life expectancy.
- **Inflation**: The negative coefficient (-0.1075) indicates that inflation may slightly decrease life expectancy, with this effect being statistically significant.

## Analysis of High-Income Countries

A subset of high-income countries was examined to see how health expenditure relates to life expectancy:

- **United States**: Despite having the highest healthcare expenditure (17.9% of GDP), the U.S. does not have the highest life expectancy (78.7 years). This suggests that higher spending does not always result in better health outcomes.
- **Singapore**: Singapore has the highest life expectancy (82.7 years) among the countries examined, with relatively moderate health expenditure (3.96% of GDP), pointing to the importance of healthcare efficiency.

## Conclusion

The analysis confirms a strong positive relationship between income and life expectancy, and suggests that while higher health expenditure can positively affect life expectancy, the efficiency of healthcare systems plays a crucial role. Inflation appears to have a small but negative effect on life expectancy. Further analysis could include variables such as healthcare infrastructure and government policies to deepen the understanding of factors influencing life expectancy.