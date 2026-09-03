## Day 81 - Batch Gradient Descent from Scratch

Today I learned about Batch Gradient Descent and implemented it from scratch for Linear Regression with multiple input features.

### Topics Covered

- Batch Gradient Descent
- Gradient Descent for multiple dimensions
- Multiple input features
- Slope/weight for multiple features
- Intercept
- Loss function
- Gradient calculation
- Simultaneous parameter updates
- Learning rate
- Iterations
- Implementing Gradient Descent from scratch

### Key Concepts Learned

- In a multiple-feature Linear Regression model, there is a separate weight for each input feature.
- The model uses all training samples in each iteration to calculate the gradients.
- This approach is called Batch Gradient Descent.
- The gradients are calculated for all weights and the intercept.
- All parameters are updated repeatedly to reduce the loss.
- The learning rate controls the size of each parameter update.

### Practical Work

Today I extended my previous understanding of Gradient Descent from a single feature to multiple dimensions.

Instead of working with only one slope and one intercept, I implemented Gradient Descent for a dataset containing multiple input columns.

The implementation was done from scratch to understand what happens mathematically during the training process instead of relying directly on a Machine Learning library.

### Batch Gradient Descent Process

1. Initialize the weights and intercept.
2. Calculate predictions using all input features.
3. Calculate the loss.
4. Calculate the gradient for every weight and the intercept.
5. Update all parameters.
6. Repeat the process for a specified number of iterations.
7. Continue until the loss gradually decreases toward a minimum.

### Key Takeaway

Today I understood how Gradient Descent extends from one-dimensional Linear Regression to multiple dimensions.

The biggest learning was that when there are n input features, the model has multiple weights, and Batch Gradient Descent updates all of them together using the entire training dataset in every iteration.

Implementing it from scratch helped me understand the mathematical foundation behind how Multiple Linear Regression learns its parameters.
