# Day 90 — Loss Function, Maximum Likelihood and Binary Cross Entropy

Today I learned about the Loss Function, Maximum Likelihood Estimation, and Binary Cross Entropy in the context of Logistic Regression.

## Topics I Learned

### 1. Loss Function

A loss function measures how different the model's predictions are from the actual values.

The goal of training the model is to minimize the loss so that the predictions become better.

```text
Prediction
     ↓
Compare with Actual Value
     ↓
Calculate Loss
     ↓
Update Model
     ↓
Better Prediction
```

### 2. Maximum Likelihood Estimation

Maximum Likelihood is a method used to find the model parameters that make the observed data most likely.

In Logistic Regression, the model produces probabilities, and Maximum Likelihood helps find the coefficients that maximize the likelihood of observing the actual data.

### 3. Binary Cross Entropy

Binary Cross Entropy is commonly used as the loss function for binary classification problems.

It measures the difference between the actual binary label and the predicted probability.

The loss function is:

```text
Loss = -[y log(p) + (1-y) log(1-p)]
```

Where:

* y = actual value
* p = predicted probability

### 4. Connection Between Maximum Likelihood and Binary Cross Entropy

I learned that Binary Cross Entropy is closely connected to Maximum Likelihood.

Maximum Likelihood tries to maximize the likelihood of the observed data.

Binary Cross Entropy is minimized during training.

These lead to the same objective:

```text
Maximum Likelihood
        ↓
Maximize likelihood
        ↓
Equivalent to minimizing
        ↓
Binary Cross Entropy
```

## Key Takeaway

Loss Function → Measures prediction error

Maximum Likelihood → Finds parameters that make the observed data most likely

Binary Cross Entropy → Measures the error between actual labels and predicted probabilities

These concepts helped me understand what happens mathematically behind Logistic Regression.
