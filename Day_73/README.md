## Day 72 - Simple Linear Regression

Today I focused on understanding the mathematical foundation behind how the model makes predictions.

### Topics Covered

- Mathematical intuition behind Linear Regression
- Equation of a regression line
- Slope and intercept
- Best-fit line
- Cost function
- Mean Squared Error
- How the model finds the best line
- Prediction using the regression equation

### Mathematical Understanding

I learned how Simple Linear Regression represents the relationship between an independent variable and a continuous dependent variable using a straight line.

The prediction is represented by:

y = mx + b

Where:

- y = predicted value
- x = input feature
- m = slope of the line
- b = intercept

I also understood how the model determines the best values of m and b by minimizing the error between the actual and predicted values.

### Practical Implementation

After understanding the mathematics, I implemented a simple Linear Regression model to predict a student's package based on their CGPA.

Input:
- CGPA

Target:
- Student Package

The model learns the relationship between CGPA and package and uses the learned regression line to predict the package for a new student.

### Key Concepts Learned

- How a regression line represents the relationship between two variables.
- What slope and intercept mean in a regression model.
- How predictions are generated using the regression equation.
- Why the best-fit line is required.
- How prediction errors are calculated.
- How Mean Squared Error can be used to measure prediction error.
- How the mathematical foundation connects to the implementation of Linear Regression.

### Key Takeaway

Today I understood Simple Linear Regression from both the mathematical and practical perspectives. Understanding the equation, slope, intercept, prediction error, and the idea of finding the best-fit line helped me understand what happens inside a Linear Regression model instead of treating it as a black box.
