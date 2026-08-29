## Day 77 - Assumptions of Linear Regression

Today I realized that improving the R² score is not simply about trying different techniques. Before improving a Linear Regression model, it is important to understand whether the data satisfies the assumptions of Linear Regression.

I learned about the major assumptions that need to be considered when building and analyzing a Linear Regression model.

### Topics Covered

- Linear Relationship
- Multicollinearity
- Normality of Residuals
- Homoscedasticity
- No Autocorrelation of Errors

### 1. Linear Relationship

The relationship between the independent variables and the dependent variable should be approximately linear.

If the relationship is not linear, a simple Linear Regression model may not be able to capture the underlying pattern effectively.

### 2. Multicollinearity

Multicollinearity occurs when two or more independent variables are highly correlated with each other.

This can make it difficult to determine the individual contribution of each feature and can make the regression coefficients unstable.

### 3. Normality of Residuals

Residuals are the differences between the actual values and the values predicted by the model.

For Linear Regression, the residuals are expected to follow an approximately normal distribution, especially when making statistical inferences about the model.

### 4. Homoscedasticity

Homoscedasticity means that the variance of the residuals remains approximately constant across different levels of the predicted values or independent variables.

If the spread of residuals changes significantly, the data may suffer from heteroscedasticity.

### 5. No Autocorrelation of Errors

The errors should be independent of one another.

Autocorrelation occurs when the error of one observation is related to the error of another observation. This is particularly important when working with time-series or sequential data.

### Why These Assumptions Matter

A high R² score alone does not guarantee that a Linear Regression model is appropriate.

Checking these assumptions helps us understand:

- Whether a linear model is suitable
- Whether features are highly correlated
- Whether the residuals behave appropriately
- Whether the model's errors have a constant variance
- Whether the errors are independent

### Key Takeaway

Today I learned that building a good Linear Regression model is not just about trying to increase the R² score.

Before improving the model, I need to understand the data and check whether the assumptions of Linear Regression are reasonably satisfied.

This gave me a better understanding of why a model can sometimes produce a poor R² score and why diagnosing the data is an important part of Machine Learning.
