# Session 17: Decision Trees in Machine Learning

## Topics Covered
- Introduction to Decision Trees.
- Structure of a Decision Tree.
- Splitting criteria.
- Classification and Regression Trees.

## Key Learnings

- **Decision Tree:** A supervised Machine Learning algorithm that makes predictions using a tree-like structure of decisions.
- **Root Node:** Represents the starting point of the tree.
- **Decision Node:** Represents a condition used to split the data.
- **Leaf Node:** Represents the final prediction or output.
- **Gini Impurity:** Measures how mixed the classes are within a node.
- **Entropy:** Measures the uncertainty or impurity in a dataset.
- **Information Gain:** Measures the reduction in entropy after splitting the data.

## Types of Decision Trees
- **Classification Tree:** Predicts categorical values, such as spam or not spam.
- **Regression Tree:** Predicts continuous numerical values, such as house prices.

## Common Python Tools
- `DecisionTreeClassifier()` – Creates a classification tree.
- `DecisionTreeRegressor()` – Creates a regression tree.
- `fit()` – Trains the model.
- `predict()` – Predicts outputs for new data.
- `plot_tree()` – Visualizes the decision tree.

## Key Takeaways
- Decision Trees are easy to understand and interpret.
- They can handle both classification and regression tasks.
- Deep trees may overfit the training data.
- Limiting tree depth can help improve generalization.

## Summary
Learned how Decision Trees make predictions using decision rules and explored their structure, splitting criteria, applications, and implementation using Scikit-learn.
