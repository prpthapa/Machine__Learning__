## Day 31 - Exploratory Data Analysis (Titanic Dataset)

Today I learned and practiced:

- Loading and exploring a real-world dataset (Titanic dataset)
- Understanding dataset dimensions using `shape`
- Exploring column names and previewing data with `head()`
- Identifying missing values using `isnull()`
- Calculating the percentage of missing data
- Understanding and inspecting data types using `dtypes`
- Converting columns to categorical data types using `astype('category')`
- Generating descriptive statistics with `describe()`
- Analyzing key numerical features such as Age, Fare, and SibSp

Key findings:
- The dataset contains **891 passengers** and **12 columns**.
- Missing values were found in:
  - Age: **177 values (~19.87%)**
  - Cabin: **687 values (~77.10%)**
  - Embarked: **2 values (~0.22%)**
- Converted `Survived`, `Pclass`, and `Sex` into categorical variables.
- Average passenger fare: **32.20**
- Average passenger age: **29.70 years**

This exercise helped me understand the first steps of Exploratory Data Analysis (EDA), including dataset inspection, data quality assessment, data type optimization, and statistical summarization.
