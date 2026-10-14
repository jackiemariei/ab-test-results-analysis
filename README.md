# A/B Test Results Analysis

## Project Overview

This project analyzes the results of an A/B test for an e-commerce website. The goal was to determine whether a new webpage led to a higher conversion rate than the existing webpage.

Using Python, I explored the dataset, calculated conversion rates, performed statistical hypothesis testing, and built logistic regression models to evaluate the experiment results.

## Business Question

Does the new webpage lead to a higher conversion rate than the existing webpage, and does the user's country have a significant relationship with conversion?

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib
- Statsmodels
- Jupyter Notebook
- Statistical hypothesis testing
- Logistic regression

## Analysis Process

1. **Data exploration:** Examined the dataset, checked for missing values, and reviewed the distribution of users across countries.
2. **Probability analysis:** Calculated overall conversion rates and compared conversion rates between the control and treatment groups.
3. **A/B testing:** Simulated conversion outcomes under the null hypothesis and evaluated the observed difference using a p-value and a 5% significance level.
4. **Logistic regression:** Built models to evaluate the relationship between webpage assignment, country, and conversion.

## Key Findings

- The control group had a conversion rate of **10.53%**.
- The treatment group had a conversion rate of **15.53%**.
- The treatment group had an approximately **5.01 percentage-point higher conversion rate** than the control group.
- The hypothesis test provided statistically significant evidence of a difference between the two pages.
- The logistic regression analysis did not find statistically significant effects for the US and UK country indicators at the 5% significance level.

## Conclusion

The analysis found strong statistical evidence that the treatment webpage had a higher conversion rate than the control webpage. Country did not show a statistically significant relationship with conversion in the logistic regression model.

These results support the treatment page within the scope of this experiment. Further validation would be useful before making a broader business decision.

## Project Files

- `Analyze_ab_test_results_notebook_new.ipynb`: Jupyter Notebook containing the analysis and code.
- `ab_data.csv`: Dataset used for the A/B test analysis.
- `Analyze_ab_test_results_notebook_new (4).html`: HTML version of the notebook.
- `analyze-a_b-test-results.pdf`: PDF report summarizing the experiment and findings.

## Skills Demonstrated

Exploratory data analysis, data visualization, probability, statistical hypothesis testing, simulation, logistic regression, and communicating data-driven findings.
