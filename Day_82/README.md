## Day 82 - Stochastic Gradient Descent

Today I learned about Stochastic Gradient Descent (SGD) and understood how it differs from Batch Gradient Descent.

### Topics Covered

- Stochastic Gradient Descent
- Batch Gradient Descent vs Stochastic Gradient Descent
- Advantages of Stochastic Gradient Descent
- Implementing SGD from scratch
- Parameter updates
- Learning Rate
- Learning Schedules

### Batch Gradient Descent vs Stochastic Gradient Descent

In Batch Gradient Descent, the model uses the entire training dataset to calculate the gradient before updating the parameters.

In Stochastic Gradient Descent, the model updates the parameters using one training example at a time.

This makes SGD much faster for large datasets because it does not need to process the entire dataset before every parameter update.

### Advantages of Stochastic Gradient Descent

- Faster parameter updates
- More suitable for large datasets
- Requires less memory
- Can start learning immediately from individual samples
- The randomness in updates can sometimes help the model move out of poor local regions

However, because each update is based on a single sample, the optimization path can be more noisy compared to Batch Gradient Descent.

### Practical Work

I implemented Stochastic Gradient Descent from scratch instead of directly using a library implementation.

The implementation helped me understand how the model:

1. Selects an individual training example.
2. Calculates its prediction and error.
3. Calculates the gradient.
4. Updates the parameters.
5. Repeats the process for other samples.

### Learning Schedules

I also learned about Learning Schedules and how the learning rate can change during training instead of remaining constant.

A learning schedule can start with a relatively larger learning rate and gradually reduce it as training progresses.

This can help the model take larger steps during the early stages and make smaller, more precise updates later.

### Key Takeaway

Today I understood why Stochastic Gradient Descent can be advantageous over Batch Gradient Descent, especially when working with large datasets.

Implementing SGD from scratch and learning about learning schedules helped me understand how the learning rate can be controlled throughout the training process and how this affects the optimization process.
