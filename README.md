# Multiple-Linear-Regression-Evaluation
Multiple Linear Regression analysis of marketing channels using Python and statsmodels to evaluate the impact of TV, Radio, Social Media, and Influencer advertising on Sales.


## Project Overview

This project analyzes the relationship between marketing channels and product sales using Multiple Linear Regression. The objective is to determine how advertising investments across TV, Radio, Social Media, and Influencer categories affect Sales performance.

The analysis includes:

* Exploratory Data Analysis (EDA)
* Encoding categorical variables
* Multicollinearity testing using Correlation Matrix and VIF
* Multiple Linear Regression modeling using statsmodels
* Residual diagnostics and assumption validation
* Statistical interpretation of coefficients and p-values
* Business recommendations for marketing budget allocation

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-learn
* SciPy

## Installation

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy scikit-learn
```

## Dataset Features

| Feature      | Description                    |
| ------------ | ------------------------------ |
| TV           | TV advertising budget category |
| Radio        | Radio advertising spend        |
| Social Media | Social media advertising spend |
| Influencer   | Influencer category            |
| Sales        | Product sales                  |

## Project Goals

* Build a statistically robust multiple regression model
* Identify significant marketing channels
* Detect multicollinearity issues
* Validate regression assumptions
* Generate data-driven marketing recommendations

## Key Insights

The regression model evaluates the impact of each marketing channel on Sales while controlling for other variables. The findings help determine which channels provide the strongest contribution to revenue growth.

## Business Recommendation

Marketing investments should prioritize channels with statistically significant positive coefficients and low multicollinearity impact. The final recommendations are based on Adjusted R-squared, p-values, and residual diagnostics.
