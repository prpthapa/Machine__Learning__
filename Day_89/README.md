# Day 89 — Perceptron Trick and Logistic Regression

Today I learned about the Perceptron Trick and Logistic Regression as an introduction to classification algorithms.

## Topics I Learned

### 1. Perceptron

A Perceptron is one of the simplest algorithms used for binary classification.

It calculates a weighted sum of the input features and uses a threshold to make a classification decision.

```text
Input Features
      ↓
Weighted Sum
      ↓
Threshold
      ↓
Prediction
```

### 2. Perceptron Trick

The Perceptron Trick is used to update the model's weights when the prediction is incorrect.

The basic idea is:

```text
Wrong Prediction
      ↓
Calculate Error
      ↓
Update Weights
      ↓
Make Better Predictions
```

The weights are gradually adjusted so that the model can find a decision boundary that separates the classes.

### 3. Decision Boundary

The Perceptron learns a decision boundary between different classes.

For example:

```text
Class 0  |  Decision Boundary  |  Class 1
```

The goal is to find a boundary that separates the data points into their respective classes.

### 4. Logistic Regression

Logistic Regression is a classification algorithm used mainly for binary classification.

Instead of directly producing a class such as 0 or 1, it produces a probability between 0 and 1.

The Sigmoid function is used to convert the model's output into a probability.

```text
Weighted Sum
     ↓
Sigmoid Function
     ↓
Probability
     ↓
Classification
```

### 5. Perceptron vs Logistic Regression

```text
Perceptron
↓
Uses a threshold
↓
Produces a class prediction


Logistic Regression
↓
Uses the Sigmoid function
↓
Produces probability
↓
Uses a threshold for classification
```

