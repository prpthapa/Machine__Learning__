## Day 58 - Handling Missing Categorical Data

Today I learned about techniques for handling missing values in categorical features, one of the most common preprocessing tasks in machine learning.

### Topics Covered

- Handling Missing Categorical Data
- SimpleImputer
- Most Frequent Imputation
- Missing Category Imputation

### Key Concepts Learned

- Categorical features often contain missing values that must be handled before training machine learning models.
- **SimpleImputer** from Scikit-learn provides an easy way to fill missing categorical values.
- **Most Frequent Imputation** replaces missing values with the most commonly occurring category (mode).
- **Missing Category Imputation** replaces missing values with a new category such as `"Missing"` or `"Unknown"`, allowing the model to recognize that the value was originally missing.
- The choice of imputation strategy depends on the dataset and the importance of missing information.

### Techniques Practiced

- Identifying missing categorical values
- Applying `SimpleImputer(strategy="most_frequent")`
- Applying `SimpleImputer(strategy="constant")`
- Creating a separate "Missing" category
- Comparing different categorical imputation strategies

### Key Takeaway

Handling missing categorical data is an essential preprocessing step. While **Most Frequent Imputation** is simple and effective for many datasets, **Missing Category Imputation** helps preserve information by explicitly indicating that a value was missing.
