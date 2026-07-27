## Day 63 - Outlier Detection using the 3-Sigma Rule (Standard Deviation Method)

Today I learned about **Outlier Detection** using the **3-Sigma Rule (Empirical Rule)**, a statistical technique used to identify extreme values in normally distributed data.

### Topics Covered

- What are Outliers?
- Understanding Normal Distribution
- Mean and Standard Deviation
- 3-Sigma (Empirical) Rule
- Calculating Upper and Lower Boundaries
- Detecting Outliers
- Visualizing Data Distribution using Histograms

### Key Concepts Learned

- Outliers are data points that lie significantly outside the normal range of a dataset.
- The **3-Sigma Rule** states that approximately **99.7%** of data in a normal distribution lies within **±3 standard deviations** from the mean.
- The lower and upper boundaries are calculated as:
  - Lower Boundary = Mean − 3 × Standard Deviation
  - Upper Boundary = Mean + 3 × Standard Deviation
- Any observations outside these boundaries are considered potential outliers.
- This method is suitable only for features that are approximately normally distributed.

### Techniques Practiced

- Visualizing feature distributions with Histograms and KDE plots
- Calculating mean and standard deviation
- Computing upper and lower boundaries
- Identifying outliers using conditional filtering
- Applying the technique on the **CGPA** feature of the placement dataset

### Key Takeaway

The 3-Sigma Rule is a simple and effective statistical method for detecting outliers in normally distributed data. Before applying it, it's important to verify that the feature follows a normal distribution to ensure reliable results.
