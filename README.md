# CDC-NHANES Health Data Statistical Analysis with Python

This project conducts a comprehensive statistical analysis of the National Health and Nutrition Examination Survey (NHANES) data from the 2015-2016 cycle. The analysis focuses on variables such as smoking rates, blood pressure, and body mass index (BMI) across demographic factors like age, gender, and education level to identify patterns and correlations within the dataset.

## Overview

NHANES is a program of studies designed to assess the health and nutritional status of adults and children in the United States. Combining interviews and physical examinations, NHANES provides a comprehensive dataset for health-related research. This project utilizes Python to perform statistical analyses, including univariate and multivariate analysis, confidence interval estimation, hypothesis testing, and regression analysis, to explore relationships within the NHANES data.

## Repository Structure

- **Data Files:**
  - `nhanes_2015_2016.csv`: Contains the NHANES 2015-2016 dataset.

- **Jupyter Notebooks:**
  - `Univariate_Multivariate_Analysis.ipynb`: Performs univariate and multivariate analyses to explore individual variables and their relationships.
  - `Confidence_Intervals.ipynb`: Estimates confidence intervals for various health metrics.
  - `Hypothesis_Testing.ipynb`: Conducts hypothesis tests to determine statistical significance of observed patterns.
  - `Regression_Analysis.ipynb`: Applies linear and logistic regression models to assess associations between variables.

## Key Analyses

1. **Univariate and Multivariate Analysis:**
   - Examines distributions and relationships of variables such as BMI, blood pressure, and smoking status across different demographic groups.

2. **Confidence Interval Estimation:**
   - Calculates confidence intervals to infer population parameters for health indicators.

3. **Hypothesis Testing:**
   - Tests hypotheses to evaluate associations between health outcomes and demographic factors.

4. **Regression Analysis:**
   - Utilizes regression models to quantify relationships between health metrics and predictors like age, gender, and education level.

## Tools and Libraries

- **Python Packages:**
  - `NumPy`: For numerical computations.
  - `Pandas`: For data manipulation and analysis.
  - `Matplotlib` and `Seaborn`: For data visualization.
  - `Statsmodels`: For statistical modeling and hypothesis testing.


## Insights and Findings

The analyses provide insights into how health indicators like BMI and blood pressure vary across different demographic groups. For instance, the regression analysis may reveal significant predictors of high blood pressure, while hypothesis testing can identify differences in smoking rates between education levels.

## References

- [NHANES 2015-2016 Data](https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?BeginYear=2015)

---

By following this guide, you can replicate the statistical analyses performed on the NHANES 2015-2016 data and gain insights into the health and nutritional status of the U.S. population. 
