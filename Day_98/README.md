Day 98 — Geometric Intuition of Support Vector Machines (SVM)

📚 Topics Learned

Support Vector Machine (SVM)

Decision Boundary

Hyperplane

Maximum Margin

Support Vectors

Geometric intuition of classification

🧠 What is SVM?

Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification and, in some cases, regression.

For classification, its main idea is to find a decision boundary that separates different classes while maximizing the margin between the boundary and the nearest data points.

📏 1. Decision Boundary

A decision boundary separates data points belonging to different classes.

In 2D, the boundary is a line.

In 3D, it is a plane.

In higher dimensions, it is called a hyperplane.

For a linear decision boundary, we can represent the hyperplane mathematically as:

[
w^T x + b = 0
]

Where:

w represents the weights that determine the orientation of the hyperplane.

x represents the input features.

b represents the bias or offset.

📐 2. Maximum Margin

The margin is the distance between the decision boundary and the closest data points from the classes.

SVM tries to find the boundary with the maximum possible margin.

Why is this useful?

It creates a clear separation between classes.

It can help the model generalize to unseen data.

It focuses on the data points closest to the boundary.

🎯 3. Support Vectors

Support vectors are the data points closest to the decision boundary.

These points are important because they determine the position and orientation of the maximum-margin boundary.

Changing the support vectors can change the decision boundary, while points far away from the margin often have little or no effect on a standard maximum-margin solution.
