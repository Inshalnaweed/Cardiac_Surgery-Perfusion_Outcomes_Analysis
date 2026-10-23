# Cardiac Surgery & Perfusion Outcomes Analysis

## Project Overview

This project explores cardiac surgery and cardiopulmonary bypass (CPB) outcomes using data analysis techniques. It focuses on identifying patterns and understanding how patient characteristics and perfusion-related factors may be associated with postoperative complications and intensive care unit (ICU) stay.

The project combines my clinical background in cardiac perfusion with my developing skills in data analytics.

## Objectives

- Analyze patient demographics and cardiac surgery characteristics.
- Explore the relationship between CPB time and postoperative outcomes.
- Investigate factors associated with prolonged ICU stay.
- Examine complication rates and potential clinical risk factors.
- Apply statistical methods to identify trends and relationships in the dataset.
- Develop data analysis and visualization skills using healthcare data.

## Tools and Technologies

- **Microsoft Excel:** Data cleaning, handling missing values, formulas, and preliminary statistical analysis.
- **SQL:** Data querying, filtering, aggregation, grouping, and calculating complication rates.
- **Python:** Data analysis and visualization using a Jupyter Notebook.
- **Statistics:** Descriptive statistics, correlation, hypothesis testing, and regression analysis.

## Key Analysis Areas

### 1. Data Cleaning
Prepared the dataset for analysis by checking missing values, identifying duplicates, and reviewing data consistency.

### 2. Exploratory Data Analysis
Examined patient age, CPB time, ICU stay, and other clinical variables to understand the distribution of the data.

### 3. Statistical Analysis
Used statistical techniques to explore relationships between clinical variables, including CPB time and ICU stay, and to investigate differences in patient outcomes.

### 4. Complication Analysis
Explored postoperative complications and their potential associations with CPB duration and patient characteristics.

### 5. Data Visualization
Used charts to communicate patterns and relationships in the cardiac surgery dataset.

## Key Questions and Findings

### Research Question
Is CPB time significantly associated with ICU stay after cardiac surgery?

### Hypotheses
- **Null Hypothesis (H₀):** CPB time has no significant relationship with ICU stay.
- **Alternative Hypothesis (H₁):** Longer CPB time is associated with longer ICU stay.

### Regression Results and Conclusion

The regression analysis showed that patients with longer CPB times tended to have longer ICU stays. The slope was 0.01864, and the R-squared value was 0.1316, meaning that CPB time explained approximately 13.16% of the variation in ICU stay. The p-value was extremely small (3.7202 × 10⁻³²), below the 0.05 significance level.

Based on these results, the null hypothesis was rejected, and the findings supported the alternative hypothesis. This suggests that longer CPB time is significantly associated with longer ICU stay in this dataset. However, this does not prove that longer CPB time directly causes patients to stay longer in the ICU.

## Project File
`Cardiac_Surgery&Perfusion_Outcomes_Analysis.ipynb`

The Jupyter Notebook contains the Python analysis and visualizations for the project.

## Dataset

The project uses a cardiac surgery and perfusion dataset for educational and portfolio purposes. Any synthetic data used in the analysis should not be interpreted as real patient evidence.

## Important Note

This is an educational data analytics project, not a clinical research study or a validated tool for predicting patient outcomes. Observed associations do not establish causation.

## Skills Demonstrated

- Healthcare data analysis
- Data cleaning and preparation
- SQL querying and aggregation
- Exploratory data analysis
- Descriptive and inferential statistics
- Correlation and regression analysis
- Data visualization
- Clinical problem-solving

## About Me

I am building on my background in cardiac perfusion to transition into data analytics, with a particular interest in healthcare analytics. This project demonstrates how clinical knowledge can be combined with analytical tools to explore healthcare data and communicate meaningful findings.
