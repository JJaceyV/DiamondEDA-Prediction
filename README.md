# Diamond Analysis and Price Prediction using Random Forest
## Summary
This project aims to find all the details about the diamond dataset and what possibly affects its price. Finally, it tries to predict the diamond's price based on the correlated variables. The project includes:
- Data Cleaning
- Univariate Analysis
- Hypothesis Testing to re-assure the relationship among variables 
- Bivariate Analysis
- Multivariate Analysis
- Diamond's Price Prediction using Random Forest

## Explain the techniques used in the project:
Data Cleaning
- In this step, I removed:
    - Unnecessary column
    - Duplicated rows
    - Inappropriate values
- I also used the MICE method to impute the missing values of the dataset and used IQR steps to
  handle the outliers

Univariate Analysis
- In this step, I divided the variables into numeric and categorical variables.
      - With numeric variables, I drew the boxplot, histogram, and qq-plot to have an overview of their distributions
      - With categorical variables, I drew pie charts and bar charts to acknowledge their most common values and the corresponding percentages
