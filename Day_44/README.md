## Day 44 - Feature Scaling: Standardization

Today I learned about **Feature Scaling**, one of the most important preprocessing techniques in Machine Learning.

### Topics Covered

- What is Feature Scaling?
- Why do we need Feature Scaling?
- Types of Feature Scaling
- Standardization (Z-score Normalization)
- Intuition behind Standardization
- Impact of Outliers on Standardization
- Why Feature Scaling is Important
- When to use Standardization

### Key Concepts Learned

- **Feature Scaling** transforms numerical features to a similar scale without changing their underlying meaning.
- Scaling prevents features with larger values from dominating machine learning algorithms.
- Common types of feature scaling include:
  - Standardization (Z-score Scaling)
  - Normalization (Min-Max Scaling)
- **Standardization** transforms data so that it has:
  - Mean = 0
  - Standard Deviation = 1
- Outliers can affect the mean and standard deviation, which impacts standardized values.
- Feature scaling improves the performance and convergence speed of many machine learning algorithms.

### When to Use Standardization

- K-Nearest Neighbors (KNN)
- K-Means Clustering
- Logistic Regression
- Linear Regression (Gradient Descent)
- Support Vector Machines (SVM)
- Principal Component Analysis (PCA)
- Neural Networks

This session helped me understand why feature scaling is an essential preprocessing step before training many machine learning models.
