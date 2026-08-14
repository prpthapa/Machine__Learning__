## Day 70 - PCA on MNIST using Scikit-learn

Today I applied Principal Component Analysis (PCA) practically on the MNIST dataset using Scikit-learn and explored how dimensionality reduction affects model performance.

### Topics Covered

- PCA implementation using Scikit-learn
- Applying PCA to the MNIST dataset
- Reducing 785 features into lower dimensions
- Iterating through different numbers of principal components
- Finding accuracy after PCA transformation
- Explained variance
- Eigenvalues and eigenvectors
- 2D visualization using PCA
- 3D visualization using PCA
- Comparing dimensionality reduction with model accuracy

### Practical Work

- Loaded and prepared the MNIST dataset.
- Applied PCA using Scikit-learn.
- Experimented with different numbers of principal components.
- Observed how the number of components affects classification accuracy.
- Reduced the high-dimensional MNIST data to 2 dimensions and visualized it.
- Reduced the data to 3 dimensions and created a 3D visualization.
- Examined the eigenvalues and eigenvectors associated with the principal components.
- Used explained variance to understand how much information is retained by different numbers of components.

### Key Concepts Learned

- PCA can reduce hundreds of features into a much smaller number of components while retaining important information.
- Increasing the number of principal components generally preserves more information from the original dataset.
- There is a trade-off between dimensionality reduction and model accuracy.
- The explained variance of each component tells us how much variance that component captures.
- Eigenvectors represent the directions of the principal components.
- Eigenvalues represent the amount of variance captured by those components.
- 2D and 3D PCA visualizations make high-dimensional datasets easier to understand.

### Key Takeaway

Today I moved from understanding the mathematics behind PCA to actually implementing it on a real high-dimensional dataset.

The MNIST dataset made it clear why dimensionality reduction is useful: hundreds of original features can be transformed into a much smaller number of meaningful components, while still retaining a large amount of the information needed for classification.

This helped me understand the connection between the mathematical foundation of PCA and its practical implementation using Scikit-learn.
