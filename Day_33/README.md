## Day 33 - Exploratory Data Analysis with Multiple Titanic Datasets

Today I learned and practiced:

- Calculating survival rates using `groupby()`
- Analyzing survival rates by gender (`Sex`)
- Analyzing survival rates by passenger class (`Pclass`)
- Merging datasets using `merge()`
- Exploring dataset structure with `head()`, `shape()`, and `info()`
- Identifying missing values using `isnull().sum()`
- Comparing training, test, and submission datasets

### Key Findings

#### Survival Rate by Gender
- Female survival rate: **74.20%**
- Male survival rate: **18.89%**

Female passengers had a significantly higher chance of survival. :contentReference[oaicite:0]{index=0}

#### Survival Rate by Passenger Class
- First Class: **62.96%**
- Second Class: **47.28%**
- Third Class: **24.24%**

Passengers traveling in higher classes had better survival rates. :contentReference[oaicite:1]{index=1}

#### Dataset Merging
- Merged `test.csv` and `gender_submission.csv` using the `PassengerId` column to combine passenger information with survival predictions. :contentReference[oaicite:2]{index=2}

#### Dataset Overview
- Training dataset shape: **(891, 12)**
- Test dataset shape: **(418, 11)**
- Gender submission dataset shape: **(418, 2)** :contentReference[oaicite:3]{index=3}

#### Missing Values
Training Dataset:
- Age: 177 missing values
- Cabin: 687 missing values
- Embarked: 2 missing values

Test Dataset:
- Age: 86 missing values
- Fare: 1 missing value
- Cabin: 327 missing values :contentReference[oaicite:4]{index=4}

This exercise helped me strengthen my understanding of exploratory data analysis, dataset merging, survival analysis, and missing value assessment using Pandas.
