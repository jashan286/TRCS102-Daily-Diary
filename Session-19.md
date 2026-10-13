# Session 19: Model Evaluation Metrics

## Topics Covered
- Introduction to Model Evaluation.
- Accuracy, Precision, and Recall.
- F1-Score.
- Regression Evaluation Metrics.

## Key Learnings

- **Model Evaluation:** Measures how well a Machine Learning model performs on unseen data.
- **Accuracy:** Measures the proportion of predictions that are correct.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how many actual positive cases are correctly identified.
- **F1-Score:** Combines precision and recall using their harmonic mean.
- **MAE and MSE:** Measure prediction errors in regression tasks.
- **R² Score:** Indicates how well a regression model explains variations in the target variable.

## Important Formulas

- Accuracy = (TP + TN) / (TP + TN + FP + FN)
- Precision = TP / (TP + FP)
- Recall = TP / (TP + FN)
- F1-Score = 2 × (Precision × Recall) / (Precision + Recall)

## Common Python Tools
- `accuracy_score()` – Calculates classification accuracy.
- `precision_score()` – Calculates precision.
- `recall_score()` – Calculates recall.
- `f1_score()` – Calculates the F1-score.
- `mean_absolute_error()` – Calculates mean absolute error.
- `r2_score()` – Calculates the R² score.

## Key Takeaways
- Different evaluation metrics measure different aspects of model performance.
- Accuracy alone may be misleading for imbalanced datasets.
- Precision and recall are important when false positives and false negatives have different costs.
- The choice of metric depends on the Machine Learning problem.

## Summary
Learned important classification and regression evaluation metrics and understood how they help measure and compare Machine Learning model performance.
