## Day 78 - Gradient Descent

Today I learned about Gradient Descent and focused on understanding the mathematical idea behind how a Linear Regression model can find better parameters.

### Topics Covered

- Introduction to Gradient Descent
- Mathematical intuition behind Gradient Descent
- Slope and intercept in Linear Regression
- Loss function
- Loss slope
- Learning rate
- Epochs
- Updating model parameters
- Visualizing the learning process

### Practical Work

I created a small regression dataset using `make_regression()` and first trained a Linear Regression model using Scikit-learn.

The trained model produced:

- Coefficient (m): approximately -57.99
- Intercept (b): approximately 50.20

I then explored Gradient Descent manually by initializing the intercept and using the learning rate and number of epochs to update the parameter.

### Gradient Descent Process

The basic idea I learned was:

1. Start with an initial parameter value.
2. Calculate the prediction.
3. Calculate the error.
4. Calculate the slope of the loss.
5. Update the parameter using the learning rate.
6. Repeat the process for multiple epochs.
7. Gradually move towards a better solution.

In the practical implementation, I used:

- Initial intercept: 0
- Slope: -57.99
- Learning rate: 0.01
- Epochs: 100

I also plotted the changing prediction lines to visualize how the model learns.

### Key Concepts Learned

- Gradient Descent is an optimization algorithm used to minimize a loss function.
- The gradient tells us the direction in which the loss changes.
- The learning rate controls how large each update is.
- Epochs determine how many times the parameter update process is repeated.
- By repeatedly updating the parameters, the model can move toward a solution that produces smaller prediction errors.

### Key Takeaway

Today I started understanding what happens behind the scenes when a model learns its parameters.

Instead of only using `LinearRegression()` from Scikit-learn, I explored how Gradient Descent can iteratively update parameters by using the slope of the loss function.

This helped me connect the mathematics of optimization with the learning process of Machine Learning models.
