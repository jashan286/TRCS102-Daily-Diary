# Session 20: Confusion Matrix and Model Validation

## Topics Covered
- Introduction to Confusion Matrix.
- True Positive, True Negative, False Positive, and False Negative.
- Train-Test Split.
- Cross-Validation.

## Key Learnings

- **Confusion Matrix:** A table used to compare actual and predicted class labels.
- **True Positive (TP):** The model correctly predicts the positive class.
- **True Negative (TN):** The model correctly predicts the negative class.
- **False Positive (FP):** The model incorrectly predicts the positive class.
- **False Negative (FN):** The model incorrectly predicts the negative class.
- **Train-Test Split:** Divides data into training and testing sets to evaluate model performance.
- **Cross-Validation:** Evaluates a model across multiple data splits to estimate its performance more reliably.

## Common Python Tools
- `confusion_matrix()` – Generates a confusion matrix.
- `train_test_split()` – Splits data into training and testing sets.
- `cross_val_score()` – Evaluates a model using cross-validation.
- `classification_report()` – Displays precision, recall, and F1-score.

## Key Takeaways
- A confusion matrix helps identify different types of prediction errors.
- False positives and false negatives have different consequences.
- Cross-validation helps assess model performance across different data splits.
- Proper validation helps identify overfitting and estimate generalization.

## Summary
Learned how to interpret a confusion matrix and use train-test splitting and cross-validation to evaluate Machine Learning models.
