# Day 87 — Lasso Regression

Today I learned about Lasso Regression and how L1 regularization can be used to control model complexity and reduce overfitting.

## Topics Covered

### 1. What is Lasso Regression?

Lasso Regression is Linear Regression with an L1 regularization penalty.

Instead of minimizing only the prediction error, Lasso also penalizes the absolute values of the coefficients.

The loss function becomes:

MSE + λ × sum of absolute coefficient values

### 2. How Lasso affects coefficients

Lasso shrinks the coefficients toward zero.

Unlike Ridge Regression, Lasso can make some coefficients exactly zero.

For example:

```text
Before Lasso:

Feature 1 → 8.5
Feature 2 → 4.2
Feature 3 → 1.1
Feature 4 → 0.3

After Lasso:

Feature 1 → 7.2
Feature 2 → 3.5
Feature 3 → 0
Feature 4 → 0
```

The features whose coefficients become zero are effectively removed from the model.

### 3. L1 Regularization

Lasso uses:

```text
λ × Σ|β|
```

where:

* λ controls the strength of regularization
* β represents the model coefficients
* |β| represents the absolute value of a coefficient

Higher λ → stronger regularization → more coefficient shrinkage.

### 4. Lasso vs Ridge

| Ridge Regression                                | Lasso Regression                   |
| ----------------------------------------------- | ---------------------------------- |
| L2 regularization                               | L1 regularization                  |
| Uses squared coefficients                       | Uses absolute coefficients         |
| Shrinks coefficients                            | Shrinks coefficients               |
| Usually does not make coefficients exactly zero | Can make coefficients exactly zero |
| Mainly controls large coefficients              | Can also perform feature selection |

### 5. Feature Selection

One of the important properties of Lasso is that it can automatically eliminate some features by reducing their coefficients to zero.

This makes Lasso useful when working with datasets containing many features.

## Key Takeaway

Ridge → Shrinks coefficients toward zero

Lasso → Shrinks coefficients and can make some coefficients exactly zero

Lasso Regression = Linear Regression + L1 Regularization
