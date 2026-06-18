## Day 47 - One-Hot Encoding for Nominal Categorical Data

Today I learned and practiced:

- Understanding Nominal Categorical Data
- One-Hot Encoding using Pandas
- k-1 One-Hot Encoding (`drop_first=True`)
- Converting categorical variables into numerical features
- Preparing categorical data for Machine Learning models

### Key Concepts Learned

- **Nominal Data** consists of categories that have no inherent order (e.g., Fuel Type, Brand).
- **One-Hot Encoding** converts each category into a separate binary (0 or 1) column.
- **Pandas `get_dummies()`** provides a simple way to perform One-Hot Encoding.
- **k-1 One-Hot Encoding** removes one dummy column (`drop_first=True`) to avoid the Dummy Variable Trap and reduce multicollinearity.

### Methods Practiced

- `pd.get_dummies()`
- `drop_first=True` for k-1 encoding

This session helped me understand how nominal categorical features can be transformed into numerical representations, making them suitable for machine learning algorithms.
