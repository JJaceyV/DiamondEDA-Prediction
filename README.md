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
- In this step, I divided the variables into numeric and categorical variables
    - **With numeric variables**: I drew the boxplot, histogram, and qq-plot to have an overview of their distributions
    - **With categorical variables**: I drew pie charts and bar charts to acknowledge their most common values and the corresponding percentages

Hypothesis Testing
    - I utilized the Chi-square test to test the correlation between categorical variables
    - I utilized the One-way ANOVA test to test the correlation between a categorical variable and a numeric variable
    - I utilized the Two-wat ANOVA test to test the correlation between the numeric independent variable and other categorical dependent variables

Bivariate and Multivariate
    - I visualized my testing results using stacked bars, grouped bars, and scatter plots

Diamond's Price Prediction using Random Forest
- I combined the columns that are highly correlated with each other into one column to avoid multicollinearity
- I used Label Encoder to turn categorical values into numeric ones so that it is much easier for the machine's understanding
- I built the pipeline applying Linear Regression, Decision Tree, Random Forest, and SVM to predict the diamond's price. I then compared the model that provided the best result based on MAE, MSE, and R square values.
- Finally, I created a function allowing users to freely adjust their inputs and it will provide the result based on the most well-operated that had been chosen beforehand

## Find a bug? 
If you found an issue or would like to submit an improvement to this project, please don't hesitate to pull a request
