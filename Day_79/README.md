## Day 79 - Gradient Descent

Today I learned about Gradient Descent and focused on understanding the mathematics behind how it works as an optimization algorithm.

### Topics Covered

- Mathematics behind Gradient Descent
- Understanding the loss function
- Gradient and direction of optimization
- Parameter updates
- Learning Rate
- Effect of Learning Rate
- Number of Iterations
- Visualization of Gradient Descent
- Understanding the universality of Gradient Descent

### Mathematical Understanding

I learned how Gradient Descent tries to minimize a loss function by repeatedly updating the model parameters in the direction that reduces the loss.

The gradient tells us how the loss changes with respect to the parameter, while the learning rate controls how large each update should be.

The general parameter update idea is:

New Parameter = Old Parameter - Learning Rate × Gradient

By repeating this process over multiple iterations, the parameter gradually moves toward a value that minimizes the loss function.

### Effect of Learning Rate

I also explored how the choice of learning rate affects the optimization process.

- A very small learning rate can make learning slow.
- A suitable learning rate allows the model to move toward the minimum efficiently.
- A very large learning rate can cause the algorithm to overshoot the minimum or even diverge.

### Visualization

I visualized the Gradient Descent process to understand how the parameter moves through the loss landscape toward the minimum.

This made the mathematical concept much easier to understand because I could actually observe how different learning rates change the path taken by Gradient Descent.

### Universality of Gradient Descent

I learned that Gradient Descent is not limited to one particular Machine Learning algorithm.

It is a general optimization technique that can be used to minimize different loss functions and learn parameters in many Machine Learning and Deep Learning algorithms.

### Key Takeaway

Today I understood Gradient Descent beyond simply knowing its formula.

The visualization of the optimization process, along with experimenting with different learning rates, helped me understand why the learning rate matters and how repeated parameter updates allow a model to gradually minimize its loss.

This gave me a stronger mathematical foundation for understanding how Machine Learning models learn.
