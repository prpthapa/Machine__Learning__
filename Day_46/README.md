## Day 46 - Ordinal Data and Ordinal Encoding

Today I learned about **Ordinal Data** and how to convert it into numerical form using **Ordinal Encoding**.

### Topics Covered

- What is Ordinal Data?
- Label Encoding
- How Ordinal Encoding Works

### Key Concepts Learned

- **Ordinal Data** is a type of categorical data where the categories have a meaningful order or ranking.
  - Examples:
    - Low < Medium < High
    - Poor < Average < Good < Excellent

- **Label Encoding** assigns numerical values to categories, but it does not always preserve the correct order for machine learning models.

- **Ordinal Encoding** converts ordered categorical values into numerical values while maintaining their natural ranking.

### Example

Education Level:

- High School → 0
- Bachelor's → 1
- Master's → 2
- PhD → 3

This preserves the order of the categories and allows machine learning algorithms to understand the ranking.

### Key Takeaway

Ordinal Encoding is useful when categorical variables have an inherent order, allowing machine learning models to interpret ranked categories correctly.
