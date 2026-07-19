## Day 59 - Random Sample Imputation

Today I learned about **Random Sample Imputation**, a technique used to handle missing values by replacing them with randomly selected values from the existing data.

### Topics Covered

- What is Random Sample Imputation?
- Why use Random Sample Imputation?
- Implementing Random Sample Imputation
- Comparing distributions before and after imputation
- Advantages and limitations of the technique

### Key Concepts Learned

- **Random Sample Imputation** replaces missing values with randomly selected observations from the same feature.
- It helps preserve the original distribution of the data better than mean or median imputation.
- Since actual observed values are used, the variance of the dataset is better maintained.
- This technique is suitable when the data is **Missing Completely at Random (MCAR)**.
- The randomness means different executions may produce slightly different results unless a random seed is fixed.

### Techniques Practiced

- Identifying missing values
- Randomly sampling existing values to fill missing entries
- Comparing feature distributions before and after imputation
- Evaluating the effect on variance and data distribution

### Key Takeaway

Random Sample Imputation is an effective method for preserving the original characteristics of a dataset. By replacing missing values with real observations instead of statistical estimates, it helps maintain the natural distribution while preparing data for machine learning models.
