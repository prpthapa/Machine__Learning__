## Day 32 - Data Cleaning and Feature Engineering with Titanic Dataset

Today I learned and practiced:

- Filling missing values using grouped statistics
- Using `groupby()` and `transform()` together
- Imputing missing Age values with median age based on `Pclass` and `Sex`
- Converting Pandas columns to NumPy arrays using `.values`
- Computing statistics with NumPy (`mean()`, `std()`)
- Filtering data using NumPy conditions
- Creating new features using mathematical operations
- Using `np.where()` for conditional column creation

Key tasks completed:

### Missing Value Handling
- Identified missing values in the `Age` column.
- Filled missing ages using the median age of passengers within the same passenger class and gender group.

### NumPy Analysis
- Extracted the `Fare` column as a NumPy array.
- Calculated:
  - Mean Fare: **32.20**
  - Standard Deviation: **49.67**
- Counted passengers based on fare-related conditions.

### Feature Engineering
- Created a new feature:
  - `FarePerPerson = Fare / (1 + SibSp + Parch)`
- Calculated fare contribution per family member.

### Conditional Data Transformation
- Created a new column called `AgeGroup` using `np.where()`
  - Child → Age < 18
  - Adult → Age ≥ 18

### Results
- Adults: **778**
- Children: **113**

This exercise helped me strengthen my understanding of missing value treatment, NumPy-based analysis, feature engineering, and conditional data transformation.
