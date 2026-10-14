# Day 99 — Mathematics Behind SVM and Kernel Trick



## 🧠 1. SVM Mathematical Foundation

Support Vector Machine is a supervised machine learning algorithm that finds a decision boundary separating different classes.

For a linear SVM, the decision boundary is represented by:

\[
w^T x + b = 0
\]

Where:

- \(w\) = weight vector
- \(x\) = input feature vector
- \(b\) = bias

The prediction depends on which side of the hyperplane a data point falls.

## 📏 2. Maximum Margin

SVM tries to maximize the distance between the decision boundary and the closest data points.

For a linearly separable dataset, the margin boundaries are:

\[
w^T x + b = 1
\]

\[
w^T x + b = -1
\]

The margin width is:

\[
\text{Margin} = \frac{2}{\|w\|}
\]

Maximizing this margin is equivalent to minimizing:

\[
\frac{1}{2}\|w\|^2
\]

subject to the classification constraints:

\[
y_i(w^T x_i+b)\geq 1
\]

Here, \(y_i\) represents the class label, usually \(-1\) or \(+1\).

This is the hard-margin SVM objective, which assumes the data can be perfectly separated by a hyperplane.

## 🎯 3. Support Vectors

Support vectors are the training points closest to the decision boundary.

They determine the position of the maximum-margin hyperplane. In the optimization formulation, these points are especially important because they constrain the margin.

## 🔄 4. What if the Data Is Not Linearly Separable?

Some datasets cannot be separated properly by a straight line or hyperplane in their original feature space.

For example, imagine one class surrounded by another class. A linear boundary may not separate them effectively.

SVM can address nonlinear patterns using kernel functions.

## 💡 5. Understanding the Kernel Trick

The Kernel Trick allows SVM to calculate similarities between data points as though they were mapped into a higher-dimensional feature space, without explicitly computing the transformed feature vectors.

A kernel function is commonly written as:

\[
K(x,z)=\phi(x)^T\phi(z)
\]

Where:

- \(x,z\) = input data points
- \(\phi\) = transformation into a feature space
- \(K(x,z)\) = similarity calculated through the kernel

This can make nonlinear classification possible while avoiding the direct computation of potentially large feature transformations.

## 🧮 6. Common Kernel Functions

### Linear Kernel

\[
K(x,z)=x^Tz
\]

- Suitable when a linear decision boundary works well.
- Computes the ordinary dot product.

### Polynomial Kernel

\[
K(x,z)=(\gamma x^Tz+r)^d
\]

- Can represent more complex relationships.
- The degree \(d\) controls the polynomial degree.

### RBF (Radial Basis Function) Kernel

\[
K(x,z)=\exp(-\gamma\|x-z\|^2)
\]

- Commonly used for nonlinear classification.
- Measures similarity based on the distance between data points.
- The parameter \(\gamma\) controls how quickly similarity decreases with distance.

## ⚖️ 7. Hard Margin vs. Soft Margin

- Hard-margin SVM requires perfect separation and is sensitive to overlapping data and outliers.
- Soft-margin SVM allows some violations to achieve a more flexible boundary.

The soft-margin objective is:

\[
\min_{w,b,\xi}\frac{1}{2}\|w\|^2+C\sum_i\xi_i
\]

subject to:

\[
y_i(w^Tx_i+b)\geq 1-\xi_i
\]

\[
\xi_i\geq0
\]

Here:

- \(\xi_i\) = slack variables that allow margin violations.
- \(C\) = trade-off between maximizing the margin and penalizing violations.

A larger \(C\) penalizes violations more strongly, while a smaller \(C\) allows more violations in exchange for a potentially wider margin.

## 🔗 8. Learning Flow

```text
Input Dataset
      ↓
Find a Decision Boundary
      ↓
Maximize the Margin
      ↓
Identify Support Vectors
      ↓
Check for Nonlinear Patterns
      ↓
Apply a Suitable Kernel
      ↓
Build the Classification Boundary
      ↓
Predict the Class
```



## 🔄 Learning Progress

Geometric Intuition of SVM → Mathematical Optimization → Support Vectors → Kernel Trick → Nonlinear Classification
