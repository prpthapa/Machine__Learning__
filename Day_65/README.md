## Day 65 - Outlier Detection using Percentile Method

Today I learned about the Percentile Method for detecting and handling outliers, a simple and effective approach that uses percentile boundaries instead of statistical measures like standard deviation or IQR.

### Topics Covered

- What is the Percentile Method?
- Choosing percentile thresholds
- Calculating upper and lower percentile boundaries
- Detecting outliers
- Handling outliers using Trimming
- Handling outliers using Capping
- Visualizing data using Histograms and Box Plots

### Key Concepts Learned

- The Percentile Method identifies outliers by selecting lower and upper percentile limits.
- Common choices are the 1st & 99th percentiles or the 5th & 95th percentiles, depending on the dataset.
- Values outside these boundaries are considered potential outliers.
- Trimming removes observations outside the selected percentile range.
- Capping replaces extreme values with the corresponding percentile boundaries instead of removing them.
- This method is simple to implement and works well when the data is not perfectly normally distributed.

### Techniques Practiced

- Calculating percentile boundaries using `quantile()`
- Detecting outliers using conditional filtering
- Removing outliers through Trimming
- Handling outliers using Capping with `np.where()`
- Comparing distributions before and after preprocessing using Histograms and Box Plots

### Dataset Used

- Weight-Height Dataset

### Key Takeaway

The Percentile Method is a practical technique for handling extreme values by defining custom percentile boundaries. Depending on the problem, outliers can either be removed through Trimming or limited using Capping, helping improve data quality while preserving important information.
