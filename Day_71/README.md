## Day 71 - PCA with Wine Dataset

Today I applied Principal Component Analysis (PCA) on the Wine dataset using Scikit-learn and explored how dimensionality reduction affects the performance of a KNN classification model.

### Dataset

The Wine dataset contains 178 observations and 13 input features along with a class label.

The features include:

- Alcohol
- Malic acid
- Ash
- Alcalinity of ash
- Magnesium
- Total phenols
- Flavanoids
- Nonflavanoid phenols
- Proanthocyanins
- Color intensity
- Hue
- Diluted wines
- Proline

### Topics Covered

- Loading and understanding the Wine dataset
- Separating features and target
- Train-test split
- Feature standardization using StandardScaler
- PCA using Scikit-learn
- Reducing dimensionality using different numbers of principal components
- KNN classification after PCA
- Comparing accuracy for different numbers of components
- 2D PCA visualization
- 3D PCA visualization

### Practical Work

First, I separated the class column from the 13 input features and divided the data into training and testing sets.

I then standardized the features using StandardScaler before applying PCA.

After that, I iterated through 1 to 10 principal components and trained a KNN classifier with 3 neighbors for each PCA configuration.

### Accuracy Results

| Principal Components | Accuracy |
|----------------------|----------|
| 1 | 0.7778 |
| 2 | 1.0000 |
| 3 | 1.0000 |
| 4 | 0.9444 |
| 5 | 0.9444 |
| 6 | 0.9722 |
| 7 | 0.9722 |
| 8 | 0.9722 |
| 9 | 0.9444 |
| 10 | 0.9444 |

The highest accuracy in this experiment was 100% with 2 and 3 principal components.

### Visualization

I reduced the standardized Wine dataset to:

- 2 principal components for a 2D scatter plot
- 3 principal components for a 3D scatter plot

The classes were represented using different colors, making it easier to observe the separation between wine classes after dimensionality reduction.

### Key Concepts Learned

- PCA can reduce the number of features while retaining important information.
- Standardization is performed before PCA so that features with different scales do not dominate the analysis.
- The number of principal components can have a significant effect on model performance.
- PCA can make high-dimensional data easier to visualize.
- KNN can be applied after PCA using the transformed principal components instead of the original features.

### Key Takeaway

Today I understood PCA from a more practical perspective. Instead of using all 13 original features of the Wine dataset, I experimented with fewer principal components and observed how dimensionality reduction affected KNN accuracy.

The experiment showed that reducing the data to only 2 or 3 principal components was enough to achieve 100% accuracy on this particular train-test split, while also making the data much easier to visualize.
