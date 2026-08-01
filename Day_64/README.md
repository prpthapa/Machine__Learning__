## Day 64 - Outlier Detection using the IQR Method

Today I learned about **Outlier Detection using the Interquartile Range (IQR) Method**, a robust statistical technique for identifying and handling outliers in skewed datasets.

### Topics Covered

- What is the IQR (Interquartile Range)?
- Calculating Quartiles (Q1 & Q3)
- Computing the IQR
- Finding Upper and Lower Boundaries
- Detecting Outliers
- Handling Outliers using Trimming
- Handling Outliers using Capping (Winsorization)
- Visualizing Outliers with Box Plots and Histograms

### Key Concepts Learned

- The **Interquartile Range (IQR)** measures the spread of the middle 50% of the data.
- Quartiles are calculated as:
  - **Q1 (25th Percentile)**
  - **Q3 (75th Percentile)**
- The IQR is calculated using:
  - **IQR = Q3 − Q1**
- Outlier boundaries are defined as:
  - **Lower Boundary = Q1 − 1.5 × IQR**
  - **Upper Boundary = Q3 + 1.5 × IQR**
- Any observations outside these boundaries are considered potential outliers.
- The IQR method is especially useful for **skewed distributions** because it is less affected by extreme values than methods based on the mean and standard deviation.

### Techniques Practiced

- Visualizing distributions using Histograms and Box Plots
- Calculating Q1, Q3, and IQR
- Computing upper and lower outlier boundaries
- Identifying outliers using conditional filtering
- Removing outliers using **Trimming**
- Limiting extreme values using **Capping (Winsorization)**
- Comparing data distributions before and after outlier treatment

### Dataset Used

- Placement Dataset (`placement_exam_marks` feature)

### Key Takeaway

The IQR method is one of the most reliable techniques for detecting outliers in skewed data. Depending on the problem, outliers can either be removed through **Trimming** or retained by limiting their values using **Capping**, helping improve data quality while preserving important information.
