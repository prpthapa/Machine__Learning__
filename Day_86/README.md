# Day 86 — Ridge Regression

Today I learned about Ridge Regression and how regularization affects the coefficients of a Linear Regression model.

## Topics Covered

### 1. How coefficients get affected

Ridge Regression adds a penalty for large coefficient values.

This causes the coefficients to shrink toward zero instead of allowing them to become unnecessarily large.

### 2. Higher values are impacted more

Ridge uses the squared values of the coefficients.

For example:

* 2² = 4
* 10² = 100

Therefore, larger coefficients receive a much higher penalty and are affected more strongly.

### 3. Impact on the Bias-Variance Tradeoff

Ridge Regression controls model complexity by shrinking the coefficients.

This generally results in:

* Slightly higher bias
* Lower variance
* Reduced overfitting
* Better generalization

### 4. Effect on the Loss Function

Ridge adds an L2 regularization term to the ordinary Linear Regression loss function.

The loss becomes:

MSE + λ × sum of squared coefficients

Here, λ (lambda) controls the strength of regularization.

* Small λ → weaker regularization
* Large λ → stronger regularization

### 5. Why is it called Ridge Regression?

I learned the mathematical and geometrical intuition behind the name "Ridge Regression" and how the regularization constraint affects the coefficient space.

### 6. Practical Application

Ridge Regression can be useful when:

* The dataset has many features
* Features are correlated
* Coefficients become very large
* The Linear Regression model is overfitting

## Key Takeaway

Ridge Regression uses L2 regularization to shrink coefficients and control model complexity.

Large coefficients → Larger penalty → Coefficients shrink → Lower variance → Less overfitting
