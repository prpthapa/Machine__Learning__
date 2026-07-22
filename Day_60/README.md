## Day 60 - Missing Indicator

Today I learned about the **Missing Indicator** technique, a feature engineering method used to preserve information about missing values while performing imputation.

### Topics Covered

- What is a Missing Indicator?
- Why Missing Indicators are useful
- Creating Missing Indicator features
- Combining Missing Indicators with Imputation
- Implementing Missing Indicators using Scikit-learn

### Key Concepts Learned

- A **Missing Indicator** creates a new binary feature that records whether the original value was missing.
- The indicator column contains:
  - **1** → Value was missing
  - **0** → Value was present
- Missing Indicators are often used alongside imputation techniques such as Mean, Median, or Most Frequent Imputation.
- They help machine learning models learn whether the absence of data itself carries useful information.
- Scikit-learn supports Missing Indicators through `SimpleImputer(add_indicator=True)` and the `MissingIndicator` transformer.

### Techniques Practiced

- Creating binary indicator columns
- Using `SimpleImputer(add_indicator=True)`
- Using `MissingIndicator`
- Combining imputation with missing indicators
- Comparing datasets before and after preprocessing

### Key Takeaway

Missing values can sometimes contain meaningful information. Instead of simply replacing them, adding a Missing Indicator allows machine learning models to capture patterns related to missing data, potentially improving model performance.
