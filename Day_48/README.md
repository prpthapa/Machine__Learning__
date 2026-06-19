## Day 48 - Column Transformer in Scikit-learn

Today I learned and practiced:

- Introduction to `ColumnTransformer`
- Why `ColumnTransformer` is needed
- Applying different preprocessing techniques to different columns
- Combining multiple transformers into a single pipeline
- Preprocessing numerical and categorical features together
- Preparing datasets efficiently for machine learning models

### Key Concepts Learned

- `ColumnTransformer` allows different transformations to be applied to different columns of a dataset simultaneously.
- It simplifies preprocessing by combining multiple operations into a single object.
- Common transformations include:
  - Standardization for numerical features
  - One-Hot Encoding for nominal categorical features
  - Ordinal Encoding for ordinal categorical features
- It integrates seamlessly with Scikit-learn Pipelines, making machine learning workflows cleaner and more efficient.

### Example Use Cases

- Scaling numerical columns while encoding categorical columns.
- Applying different preprocessing steps without manually separating the dataset.
- Building reusable and production-ready machine learning pipelines.

This session helped me understand how `ColumnTransformer` simplifies feature preprocessing and makes machine learning pipelines more organized and scalable.
