# Day 75 — Introduction to Multiple Linear Regression

Today I learned about **Multiple Linear Regression**, an extension of simple linear regression.

## What I learned

In simple linear regression, we use one independent variable to predict a dependent variable.

In multiple linear regression, we use **multiple independent variables** to predict the target.

For example, when predicting house prices, we could use:

* House area
* Number of bedrooms
* Number of bathrooms
* Location-related features
* Number of floors

The general form of the model is:

**y = b₀ + b₁x₁ + b₂x₂ + ... + bₙxₙ**

Where:

* `y` = predicted target
* `b₀` = intercept
* `x₁, x₂, ..., xₙ` = input features
* `b₁, b₂, ..., bₙ` = coefficients

## Dataset Practice

I used datasets to understand how multiple features are arranged and how they are used to train a regression model.

The workflow I practiced was:

1. Load the dataset
2. Identify the features and target
3. Separate `X` and `y`
4. Split the data into training and testing sets
5. Train a Multiple Linear Regression model
6. Make predictions
7. Evaluate the model

## Key Takeaway

The main thing I understood today is that **real-world predictions usually depend on multiple factors**, so multiple linear regression allows us to consider several features simultaneously.

This was another important step in my Machine Learning journey.

**Day 75 completed. 🚀**
