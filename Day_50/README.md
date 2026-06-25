## Day 50 - Function Transformer and Data Transformations

Today I learned and practiced:

- Function Transformer
- How to determine whether data follows a normal distribution
- Log Transformation
- Reciprocal Transformation
- Square Transformation
- Applying transformations on the Titanic Dataset

### Key Concepts Learned

- **FunctionTransformer** allows custom mathematical transformations to be applied to features within Scikit-learn pipelines.
- Before applying transformations, it is important to check whether the data follows a **normal distribution**.
- **QQ Plots** help compare a dataset's distribution against a theoretical normal distribution.
- **Log Transformation** reduces skewness and handles large value ranges.
- **Reciprocal Transformation** can reduce the impact of large values and improve distribution shape.
- **Square Transformation** can help adjust data distributions depending on feature characteristics.
- Different transformations affect data differently, so selecting the right one depends on the dataset.

### Techniques Practiced

- QQ Plot analysis
- Log Transform
- Reciprocal Transform
- Square Transform
- FunctionTransformer implementation
- Titanic Dataset transformation examples

### Key Takeaway

Data transformations are powerful preprocessing techniques that help make data more suitable for machine learning algorithms by improving distribution characteristics and reducing skewness.
