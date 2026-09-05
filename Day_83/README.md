## Day 83 - Mini-Batch Gradient Descent

Today I learned about Mini-Batch Gradient Descent and understood how it combines ideas from both Batch Gradient Descent and Stochastic Gradient Descent.

### Topics Covered

- Mini-Batch Gradient Descent
- Batch Gradient Descent vs Stochastic Gradient Descent vs Mini-Batch Gradient Descent
- Mini-batch size
- Parameter updates
- Learning rate
- Implementing Mini-Batch Gradient Descent from scratch
- Contour visualization
- Understanding the optimization path

### Understanding Mini-Batch Gradient Descent

Mini-Batch Gradient Descent divides the training dataset into smaller groups called mini-batches.

Instead of:

- Using the entire dataset like Batch Gradient Descent
- Using only one sample like Stochastic Gradient Descent

Mini-Batch Gradient Descent uses a small number of samples to calculate the gradient and update the parameters.

For example:

```text
Dataset
   ↓
[ Mini-Batch 1 ] → Update parameters
[ Mini-Batch 2 ] → Update parameters
[ Mini-Batch 3 ] → Update parameters
       ...
