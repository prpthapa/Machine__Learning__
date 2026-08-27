## Day 76 - Practicing Multiple Linear Regression

Today I practiced Multiple Linear Regression using a House Price Prediction dataset.

The main goal was to use multiple features together to predict the price of a house.

### Dataset Features

The dataset contained features such as:

- Area
- Bedrooms
- Bathrooms
- Floors
- YearBuilt
- Location
- Condition
- Garage
- Price

### Topics Practiced

- Loading and exploring the dataset
- Understanding numerical and categorical features
- Splitting features and target
- Train-test split
- Encoding categorical variables
- ColumnTransformer
- Multiple Linear Regression
- Making predictions
- Regression evaluation metrics
- MAE
- MSE
- RMSE
- R² Score

### Data Preprocessing

The categorical features were:

- Location
- Condition
- Garage

I used OrdinalEncoder through ColumnTransformer to convert these categorical values into numerical representations before training the Linear Regression model.

### Model Performance

The first model did not perform well.

Results:

- MAE: 244272.25
- MSE: 78803223997.04
- RMSE: 280719.12
- R²: -0.0129

The negative R² score showed that the model was not explaining the target variable well in this experiment.

### What I Learned

Getting a poor model result is also an important part of Machine Learning.

Instead of considering the negative R² as a failure, I am treating it as a problem to investigate.

Possible areas I will explore next:

- Feature engineering
- Better handling of categorical features
- Removing irrelevant features
- Checking the relationship between features and price
- Outlier analysis
- Trying different preprocessing techniques
- Comparing different regression models
- Improving model performance

### Key Takeaway

Today was more about understanding the practical side of Machine Learning than just getting a good score.

The negative R² showed me that simply applying Multiple Linear Regression does not guarantee good predictions. The quality of the features, preprocessing, and relationship between the input features and target are extremely important.

Tomorrow I will investigate why the model performed poorly and try to improve its performance.
