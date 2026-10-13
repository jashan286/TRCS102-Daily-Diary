# Session 18: Random Forest Algorithm

## Topics Covered
- Introduction to Random Forest.
- Ensemble Learning.
- Bagging Technique.
- Model Training and Evaluation.

## Key Learnings

- **Random Forest:** A supervised Machine Learning algorithm that combines multiple decision trees to make predictions.
- **Ensemble Learning:** Combines multiple models to improve prediction performance.
- **Bagging:** Trains multiple models on different bootstrap samples of the training data.
- **Voting:** For classification, the trees' predictions are combined, commonly using majority voting.
- **Averaging:** For regression, predictions from multiple trees are commonly averaged.
- **Feature Randomness:** Each tree considers a random subset of features when searching for splits, helping create diverse trees.

## Common Python Tools
- `RandomForestClassifier()` – Creates a classification model.
- `RandomForestRegressor()` – Creates a regression model.
- `fit()` – Trains the model.
- `predict()` – Generates predictions.
- `feature_importances_` – Provides impurity-based feature importance scores.

## Key Takeaways
- Random Forest combines multiple decision trees.
- It can perform both classification and regression.
- It often reduces overfitting compared with a single deep decision tree.
- The number of trees and maximum tree depth can affect model performance.

## Summary
Learned how Random Forest uses ensemble learning and bagging to combine multiple decision trees, improve prediction performance, and solve classification and regression problems.
