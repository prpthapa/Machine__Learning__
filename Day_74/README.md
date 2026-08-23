## Day 74 - Regression Metrics

Today I learned about different evaluation metrics used to measure the performance of Regression models and practiced them using a dataset containing CGPA and Placement information.

### Topics Covered

- Regression Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R² Score
- Comparing actual and predicted values

### Metrics Learned

#### Mean Absolute Error (MAE)

MAE calculates the average absolute difference between the actual and predicted values.

It gives an idea of how much the predictions differ from the actual values on average.

#### Mean Squared Error (MSE)

MSE calculates the average of the squared differences between actual and predicted values.

Since the errors are squared, larger errors have a greater impact on the metric.

#### Root Mean Squared Error (RMSE)

RMSE is the square root of MSE.

It brings the error back to the same unit as the target variable, making it easier to interpret.

#### R² Score

R², or the coefficient of determination, measures how well the regression model explains the variation in the target variable.

A higher R² generally indicates that the model explains more of the variation in the target.

#### Adjusted R² Score

Adjusted R² is a modified version of R² that takes the number of features used by the model into account.

It is useful when comparing regression models with different numbers of input features.

### Practical Work

I practiced these regression metrics using a dataset containing:

- CGPA
- Placement

I used the model's predictions and compared them with the actual placement values to calculate and understand each regression metric.

### Key Takeaway

Different regression metrics provide different perspectives on model performance. MAE, MSE, and RMSE measure prediction error, while R² and Adjusted R² help understand how well the model explains the variation in the target variable.

Understanding these metrics is important because simply training a regression model is not enough; we also need reliable ways to evaluate how well it performs.
