## Day 85 - Bias-Variance Tradeoff

Today I learned about the Bias-Variance Tradeoff and understood the concepts of underfitting and overfitting.

### Topics Covered

- Bias
- Variance
- Bias-Variance Tradeoff
- Underfitting
- Overfitting
- Model complexity
- Choosing the appropriate model

### Underfitting

Underfitting happens when a model is too simple to properly capture the underlying patterns in the data.

The model performs poorly on both the training data and unseen data.

This generally indicates that the model has high bias.

### Overfitting

Overfitting happens when a model becomes too complex and starts learning the noise and specific patterns of the training data.

The model performs very well on training data but performs poorly on unseen data.

This generally indicates that the model has high variance.

### Bias-Variance Tradeoff

I learned that there is a tradeoff between bias and variance.

- High Bias → Model is too simple → Underfitting
- High Variance → Model is too complex → Overfitting

The goal is not to choose the most complex model, but to find a model with the right level of complexity that generalizes well to unseen data.

### Choosing the Right Model

I learned that model selection should be based on how well the model generalizes rather than only looking at its training performance.

A useful way to think about it is:

```text
Too Simple
    ↓
Underfitting
    ↓
Good Model
    ↓
Overfitting
    ↓
Too Complex
