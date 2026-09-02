## Day 80 - Gradient Descent with Slope and Intercept

Today I continued practicing the mathematics behind Gradient Descent for Linear Regression.

Yesterday I practiced Gradient Descent by keeping one parameter constant. Today I extended the concept by updating both the slope and intercept together.

### Topics Covered

- Mathematical implementation of Gradient Descent
- Updating slope and intercept simultaneously
- Loss function
- Gradients for slope and intercept
- Parameter updates
- Effect of Learning Rate
- Effect of Loss Function
- Effect of Data on Gradient Descent
- Visualization of the optimization process

### Practical Learning

Yesterday, I kept one parameter constant while observing how Gradient Descent updated the other parameter.

Today, I used both:

- Slope
- Intercept

and updated them simultaneously during each iteration.

This helped me understand more clearly how a Linear Regression model can learn both parameters together and gradually move toward a better solution.

### Effect of Learning Rate

I explored how changing the learning rate affects the optimization process.

- Very small learning rate can make convergence slow.
- A suitable learning rate can help reach the minimum efficiently.
- A very large learning rate can cause the model to overshoot the minimum or fail to converge.

### Effect of Loss Function

I also learned that the choice of loss function affects how Gradient Descent behaves because the gradient is calculated from the loss function.

The loss function determines how the prediction error is measured and therefore influences the direction and magnitude of parameter updates.

### Effect of Data

I explored how the underlying data affects Gradient Descent.

The distribution, scale, and relationship between the input and target values influence the loss landscape and the way the parameters are updated.

### Visualization

I visualized the Gradient Descent process to observe how the slope and intercept change during optimization and how the model moves toward a lower loss.

### Key Takeaway

Today I moved one step closer to understanding Gradient Descent mathematically.

Updating both slope and intercept together helped me understand that a model learns multiple parameters simultaneously rather than adjusting only one value.

I also learned that the learning rate, loss function, and data itself can significantly affect how Gradient Descent behaves and whether it converges effectively.
