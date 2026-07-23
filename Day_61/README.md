## Day 61 - KNN Imputer

Today I learned about **KNN (K-Nearest Neighbors) Imputation**, an advanced technique for handling missing numerical data using the similarity between data points.

### Topics Covered

- KNN Imputation
- Why KNN Imputer is used
- Distance-based missing value estimation
- Implementing `KNNImputer`
- Training a Logistic Regression model after imputation
- Evaluating model performance using Accuracy Score

### Key Concepts Learned

- **KNN Imputer** fills missing values by finding the **K nearest samples** based on feature similarity.
- Instead of using statistical values like mean or median, it estimates missing values using neighboring observations.
- The `weights='distance'` parameter gives more importance to closer neighbors during imputation.
- KNN Imputation often preserves the underlying data patterns better than simple imputation methods.
- After imputation, the processed data can be directly used for training machine learning models.

### Techniques Practiced

- Handling missing values using `KNNImputer`
- Splitting data into training and testing sets
- Training a Logistic Regression model
- Predicting outcomes on test data
- Evaluating performance using Accuracy Score

### Dataset Used

- Titanic Dataset

### Key Takeaway

KNN Imputation is a powerful preprocessing technique that estimates missing values based on similar observations instead of simple statistical measures. It helps preserve relationships within the data and can improve machine learning model performance.
