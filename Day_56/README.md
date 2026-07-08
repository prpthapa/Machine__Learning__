## Day 56 - Mean and Median Imputation

Today I learned about **Mean and Median Imputation**, two common techniques used to handle missing numerical data in machine learning.

### Topics Covered

- Mean Imputation
- Median Imputation
- Comparing Mean vs Median Imputation
- Impact of Imputation on Data Distribution
- Variance and Covariance Analysis
- Correlation Analysis
- Visualizing distributions using KDE Plots and Box Plots
- Using `SimpleImputer`
- Using `ColumnTransformer` for multiple imputations

### Key Concepts Learned

- **Mean Imputation** replaces missing values with the mean of a feature.
- **Median Imputation** replaces missing values with the median, making it more robust to outliers.
- Imputation changes the statistical properties of a dataset, such as variance and covariance.
- KDE plots and box plots help visualize how imputation affects data distribution.
- **SimpleImputer** from Scikit-learn provides an efficient way to perform missing value imputation.
- **ColumnTransformer** allows different imputation strategies to be applied to different columns within the same preprocessing pipeline.

### Techniques Practiced

- Calculating mean and median values
- Filling missing values using Pandas
- Comparing distributions before and after imputation
- Analyzing variance, covariance, and correlation
- Applying `SimpleImputer`
- Building preprocessing workflows with `ColumnTransformer`

### Key Takeaway

Choosing the right imputation strategy depends on the nature of the data. While **Mean Imputation** is simple and effective for normally distributed data, **Median Imputation** is generally preferred when the dataset contains outliers. Using Scikit-learn's preprocessing tools makes the imputation process more efficient and reproducible.
