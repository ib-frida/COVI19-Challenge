# Life Expectancy and Economic Indicators Analysis

#### Project Overview

This project aims to analyze the relationship between **income**, **health expenditure**, **inflation**, and **life expectancy** across multiple countries. The dataset includes various economic and health-related indicators from different countries, and the analysis seeks to understand how these factors correlate with life expectancy. 

By employing both **correlation analysis** and **regression modeling**, the project provides insights into how income levels and health expenditure influence the life expectancy of nations, with a particular focus on high-income countries for comparison.

#### Files and Structure

1. **Dataset**:
   - The dataset contains the following columns:
     - `country`: Name of the country
     - `child_mort`: Child mortality rate
     - `exports`: Export percentage of GDP
     - `health`: Health expenditure percentage of GDP
     - `imports`: Import percentage of GDP
     - `income`: National income per capita
     - `inflation`: Annual inflation percentage
     - `life_expec`: Life expectancy in years
     - `total_fer`: Total fertility rate
     - `gdpp`: GDP per capita
     
2. **Analysis Files**:
   - **OLS Regression Results**: Results from the Ordinary Least Squares (OLS) regression model evaluating the impact of income, health expenditure, and inflation on life expectancy.
   - **Correlation Heatmap**: Visual representation of the relationships between the variables in the dataset, showing both positive and negative correlations.

3. **Output Report**:
   - A detailed report summarizing the findings from both the correlation analysis and regression modeling. It explores the relationships between income, health expenditure, and life expectancy, while highlighting key observations from high-income countries.

#### Key Findings

- **Income and Life Expectancy**: A strong positive relationship exists between national income and life expectancy. Higher-income countries tend to have longer life expectancies.
  
- **Health Expenditure**: Countries that invest more in healthcare generally see higher life expectancies, but this relationship is not always direct. Efficiency of health systems is a key factor.
  
- **Inflation**: Higher inflation may have a small but significant negative effect on life expectancy.

#### Tools Used

- **Python**: The main programming language used for analysis.
  - Libraries such as `pandas`, `statsmodels`, `seaborn`, and `matplotlib` were used for data processing, regression analysis, and visualizations.
  
- **Visualizations**:
  - **Correlation Heatmap**: Displays the correlation between different variables, helping identify significant relationships.
  - **Regression Summary**: Provides detailed statistical information on how income, health expenditure, and inflation impact life expectancy.