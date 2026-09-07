## Day 84 - Polynomial Regression

Today I learned about Polynomial Regression and implemented it from scratch to understand how it works mathematically and practically.

### Topics Covered

- Introduction to Polynomial Regression
- Polynomial features
- Mathematical intuition behind Polynomial Regression
- Relationship between degree and model complexity
- Choosing the appropriate degree
- Understanding when Linear Regression is not suitable
- Implementing Polynomial Regression from scratch
- Visualization of Polynomial Regression

### Understanding Polynomial Regression

Linear Regression works well when the relationship between the input and target is approximately linear.

But when the relationship is curved or non-linear, a straight line may not be able to capture the pattern properly.

Polynomial Regression helps by transforming the original features into polynomial features and then fitting a Linear Regression model on those transformed features.

For example, instead of using only:

x

we can create:

x, x², x³, ...

and use these features to model a curved relationship.

### Effect of Degree

I learned that the degree of the polynomial controls the complexity of the model.

- Low degree → simpler curve
- Appropriate degree → captures the underlying pattern
- Very high degree → model can become unnecessarily complex and may overfit

Therefore, choosing the degree is an important part of Polynomial Regression.

### When to Use Polynomial Regression

Polynomial Regression is useful when the relationship between the input and target is not linear and a straight line cannot represent the underlying pattern effectively.

Instead of abandoning Linear Regression completely, Polynomial Regression transforms the features so that Linear Regression can model a non-linear relationship.

### Practical Work

I implemented Polynomial Regression from scratch to understand how the polynomial features and regression model work together.

I also experimented with different polynomial degrees and visualized the resulting curves to understand how increasing the degree changes the model.

### Key Takeaway

Today I learned that Polynomial Regression is still based on the idea of Linear Regression, but polynomial features allow the model to capture non-linear relationships.

The degree of the polynomial has a major effect on the model: too low may underfit the data, while too high can make the model unnecessarily complex and prone to overfitting.

Understanding this relationship between model complexity and degree helped me better understand when Polynomial Regression can be useful.
