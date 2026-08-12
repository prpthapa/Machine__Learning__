## Day 69 - PCA: Practical Understanding with MNIST

Today I went deeper into Principal Component Analysis (PCA) by understanding the mathematical intuition behind PCA and applying it to the MNIST dataset.

### Topics Covered

- Practical Example using the MNIST Dataset
- Problem Formulation
- Covariance and Covariance Matrix
- Eigenvectors and Eigenvalues
- Visualizing Linear Transformations
- Eigendecomposition of a Covariance Matrix
- How to Solve PCA
- Transforming Points using PCA

### Key Concepts Learned

- How PCA can be used to reduce the dimensionality of a high-dimensional dataset such as MNIST.
- How the covariance matrix represents the relationships between different features.
- How eigenvectors represent the principal directions of the data.
- How eigenvalues indicate the amount of variance captured along each principal direction.
- How eigendecomposition of the covariance matrix helps identify the principal components.
- How data points are transformed into a new coordinate system using the principal components.
- How PCA can be understood geometrically through linear transformations.

### Practical Learning

The MNIST dataset was used as a practical example to understand why dimensionality reduction is useful when dealing with a large number of features.

I also worked through the mathematical process of PCA instead of treating it only as a Scikit-learn function.

### Key Takeaway

PCA became much clearer after understanding its mathematical foundation. Instead of simply using PCA as a dimensionality reduction function, I learned how covariance, eigenvectors, eigenvalues, eigendecomposition, and coordinate transformation work together to find the principal components.

This helped connect the mathematical concepts of linear algebra with their practical application in Machine Learning.
