# Session 16: K-Nearest Neighbors (KNN)

## Topics Covered
- Introduction to K-Nearest Neighbors.
- Distance calculation.
- Classification using KNN.
- Choosing the value of K.

## Key Learnings

- **KNN:** A supervised Machine Learning algorithm used for classification and regression.
- **Working Principle:** KNN predicts an output by examining the K nearest data points to a new observation.
- **Euclidean Distance:** Measures the straight-line distance between two data points.
- **Value of K:** Determines how many nearest neighbors are considered when making a prediction.
- **Classification:** Assigns a class based on the majority class among the nearest neighbors.
- **Feature Scaling:** Helps prevent features with larger numerical ranges from dominating distance calculations.

## Important Formula

Euclidean Distance:

d = √[(x₂ - x₁)² + (y₂ - y₁)²]

## Common Python Tools
- `KNeighborsClassifier()` – Creates a KNN classification model.
- `KNeighborsRegressor()` – Creates a KNN regression model.
- `fit()` – Trains the model using the training data.
- `predict()` – Predicts outputs for new data.
- `StandardScaler()` – Standardizes features before distance calculations.

## Key Takeaways
- KNN is a simple, distance-based learning algorithm.
- The value of K affects prediction results.
- Feature scaling is important for distance-based algorithms.
- KNN is used in pattern recognition, recommendation systems, and classification tasks.

## Summary
Learned how KNN works using distance calculations and neighboring data points, and understood the importance of selecting K and scaling features.
