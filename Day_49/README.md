## Day 49 - Machine Learning Pipelines

Today I learned and practiced:

- Strategy for building a Machine Learning Pipeline
- Creating Pipelines in Scikit-learn
- Difference between `Pipeline` and `make_pipeline`
- Exploring and inspecting Pipeline steps
- Performing Cross Validation using Pipelines

### Key Concepts Learned

- A **Pipeline** automates the sequence of preprocessing and model training steps.
- Pipelines help prevent data leakage by ensuring preprocessing is performed correctly on training and testing data.
- `Pipeline` allows explicit naming of steps, while `make_pipeline` automatically assigns names.
- Pipelines make machine learning workflows cleaner, reusable, and easier to maintain.
- Cross Validation can be performed directly on a Pipeline, ensuring that preprocessing is applied consistently across all folds.

### Topics Practiced

- Building end-to-end machine learning workflows
- Combining preprocessing and modeling into a single object
- Comparing `Pipeline` and `make_pipeline`
- Accessing and inspecting pipeline components
- Applying Cross Validation with pipelines

### Key Takeaway

Pipelines are an essential tool in machine learning because they streamline preprocessing, model training, and evaluation while reducing the risk of mistakes and data leakage.
