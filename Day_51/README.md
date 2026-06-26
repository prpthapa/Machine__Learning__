## Day 51 - Power Transformation

Today I learned about **Power Transformation**, a feature engineering technique used to make data more normally distributed and improve machine learning model performance.

### Topics Covered

- Introduction to Power Transformation
- Box-Cox Transformation
- Yeo-Johnson Transformation
- Checking data normality using Histograms and QQ Plots
- Applying `PowerTransformer` from Scikit-learn
- Training a Linear Regression model after transformation
- Evaluating model performance using R² Score and Cross Validation

### Key Concepts Learned

- **Power Transformation** helps reduce skewness and makes data closer to a normal distribution.
- **Box-Cox Transformation** works only with positive numerical values.
- **Yeo-Johnson Transformation** can handle both positive and negative values.
- Histograms and QQ Plots are useful tools for checking whether a feature follows a normal distribution.
- Scikit-learn's `PowerTransformer` provides an easy way to apply both Box-Cox and Yeo-Johnson transformations.
- Feature transformation can improve the performance of machine learning models by making the data more suitable for learning algorithms.

### Practical Implementation

- Loaded the Concrete Strength dataset.
- Visualized feature distributions using Histograms and QQ Plots.
- Applied:
  - Box-Cox Transformation
  - Yeo-Johnson Transformation
- Trained a Linear Regression model on transformed data.
- Evaluated the model using R² Score and Cross Validation.

### Key Takeaway

Power Transformation is an effective preprocessing technique for handling skewed numerical data. Choosing the right transformation can improve data quality and enhance the performance of machine learning models.
