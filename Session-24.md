# Session 24: Principal Component Analysis (PCA)

## Topics Covered
- Introduction to Dimensionality Reduction
- Principal Component Analysis (PCA)
- Principal Components
- Variance and Feature Selection
- Applications of PCA

## Key Learnings

### 1. Introduction to Dimensionality Reduction
Dimensionality reduction is the process of reducing the number of features in a dataset while preserving as much useful information as possible. It helps simplify data, reduce computation time, and improve visualization.

### 2. What is PCA?
Principal Component Analysis (PCA) is an unsupervised learning technique used for dimensionality reduction. It transforms the original features into a smaller set of new features called principal components.

### 3. Principal Components
- Principal components are new variables created from combinations of the original features.
- The first principal component captures the maximum possible variance in the data.
- The second principal component captures the maximum remaining variance and is perpendicular to the first.
- Additional components capture the remaining variance in decreasing order.

### 4. Steps in PCA
1. Standardize the dataset when features have different scales.
2. Calculate the covariance matrix.
3. Find eigenvalues and eigenvectors.
4. Select the principal components with the highest eigenvalues.
5. Transform the original data into the selected components.

### 5. Advantages and Limitations

**Advantages:**
- Reduces the number of features.
- Can improve computational efficiency.
- Helps visualize high-dimensional data.
- May reduce noise and redundancy.

**Limitations:**
- Principal components can be difficult to interpret.
- Some information may be lost.
- Results depend on data scaling and feature relationships.

## Common Python Tools
Using Python's `scikit-learn` library:
- `StandardScaler()` – Standardizes features.
- `PCA()` – Creates a PCA model.
- `fit()` – Learns the principal components.
- `transform()` – Converts data into principal components.
- `fit_transform()` – Learns and applies the transformation.
- `explained_variance_ratio_` – Shows the proportion of variance explained by each component.

## Key Takeaways
- PCA is used for dimensionality reduction.
- It converts original features into principal components.
- Components are ordered by the amount of variance they capture.
- Standardization is important when features use different scales.
- PCA can simplify datasets while retaining important information.

## Summary
In this session, I learned about Principal Component Analysis (PCA) and its role in dimensionality reduction. I studied principal components, variance, and the steps involved in applying PCA. I also explored Python tools used to reduce features and analyze how much information the selected components retain.
