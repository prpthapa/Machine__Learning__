## Day 57 - Arbitrary Value Imputation

Today I learned about **Arbitrary Value Imputation**, a technique for handling missing numerical data by replacing missing values with a fixed constant.

### Topics Covered

- What is Arbitrary Value Imputation?
- Choosing arbitrary values for missing data
- Impact of arbitrary values on data distribution
- Variance and covariance analysis
- Correlation analysis
- Visualizing distributions using KDE plots
- Using `SimpleImputer` with the `constant` strategy
- Applying multiple imputations using `ColumnTransformer`

### Key Concepts Learned

- **Arbitrary Value Imputation** replaces missing values with a predefined constant (e.g., 99, 999, or -1).
- The chosen value should be outside the normal range of the feature so it can be easily identified by the model.
- This technique preserves all observations while explicitly indicating missing data.
- Using extreme values may significantly affect statistical properties such as variance and data distribution.
- `SimpleImputer(strategy='constant')` provides an easy way to implement arbitrary value imputation in Scikit-learn.
- `ColumnTransformer` allows different constant values to be applied to different columns within the same preprocessing pipeline.

### Techniques Practiced

- Filling missing values with constants (99, 999, and -1)
- Comparing distributions using KDE plots
- Analyzing variance, covariance, and correlation
- Applying `SimpleImputer(strategy='constant')`
- Building preprocessing pipelines with `ColumnTransformer`

### Key Takeaway

Arbitrary Value Imputation is useful when we want to preserve missing information instead of estimating it. However, the selected constant should be chosen carefully, as it can influence the statistical properties of the dataset and the performance of machine learning models.
