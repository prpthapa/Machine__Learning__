# Day 88 — Elastic Net Regression

Today I learned about Elastic Net Regression, which combines the regularization techniques of Ridge Regression and Lasso Regression.

## Topics Covered

### 1. What is Elastic Net Regression?

Elastic Net combines:

* L1 regularization from Lasso
* L2 regularization from Ridge

So the model gets the benefits of both approaches.

Conceptually:

```text
Elastic Net
    ↓
L1 Regularization + L2 Regularization
    ↓
Lasso + Ridge
```

### 2. Loss Function

Elastic Net adds both L1 and L2 penalties to the Linear Regression loss function.

```text
Loss = MSE + λ₁Σ|β| + λ₂Σβ²
```

Where:

* λ₁ controls the L1 penalty
* λ₂ controls the L2 penalty
* β represents the model coefficients

### 3. Effect on Coefficients

Elastic Net can shrink coefficients toward zero like Ridge and can also make some coefficients exactly zero like Lasso.

Therefore:

```text
Ridge → Shrinks coefficients

Lasso → Shrinks coefficients + Can make them zero

Elastic Net → Shrinks coefficients + Can make some zero
```

### 4. Why Combine Ridge and Lasso?

Lasso can perform feature selection by making coefficients zero, but it can have difficulties when features are highly correlated.

Ridge handles correlated features by distributing the effect among them.

Elastic Net combines these behaviors, making it useful when there are many features and some of them are correlated.

### 5. Bias-Variance Tradeoff

Like Ridge and Lasso, Elastic Net adds regularization to control model complexity.

Increasing regularization can:

* Increase bias
* Reduce variance
* Reduce overfitting
* Improve generalization

The regularization strength needs to be chosen carefully.

## Ridge vs Lasso vs Elastic Net

| Method      | Regularization | Can make coefficients zero? |
| ----------- | -------------- | --------------------------- |
| Ridge       | L2             | Usually No                  |
| Lasso       | L1             | Yes                         |
| Elastic Net | L1 + L2        | Yes                         |

## Key Takeaway

Elastic Net combines the strengths of Ridge and Lasso.

Ridge → L2

Lasso → L1

Elastic Net → L1 + L2

Today I learned how combining both regularization techniques can provide a useful balance between coefficient shrinkage and feature selection.

