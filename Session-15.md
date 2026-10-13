# Session 15: Logistic Regression for Classification

## Topics Covered
- Introduction to Logistic Regression.
- Binary Classification.
- Sigmoid Function.
- Model Training and Evaluation.

## Key Learnings

- **Logistic Regression:** A supervised Machine Learning algorithm used to predict the probability of a class.
- **Binary Classification:** Classifies data into two categories, such as spam or not spam.
- **Sigmoid Function:** Converts a numerical score into a probability between 0 and 1.
- **Decision Threshold:** A cutoff, commonly 0.5, used to assign a predicted class based on probability.
- **Model Training:** The algorithm learns relationships between input features and class labels.
- **Model Evaluation:** Metrics such as accuracy, precision, recall, and F1-score help evaluate classification performance.

## Important Formula

Sigmoid Function:

σ(z) = 1 / (1 + e^(-z))

Where:
- z = Model's numerical output
- σ(z) = Predicted probability between 0 and 1

## Common Python Tools
- `LogisticRegression()` – Creates a logistic regression model using Scikit-learn.
- `fit()` – Trains the model.
- `predict()` – Predicts class labels.
- `predict_proba()` – Estimates class probabilities.
- `accuracy_score()` – Measures the proportion of correct predictions.
- `confusion_matrix()` – Summarizes actual and predicted classes.

## Key Takeaways
- Logistic Regression is mainly used for classification, not continuous-value prediction.
- The sigmoid function converts scores into probabilities.
- A decision threshold helps determine the predicted class.
- Logistic Regression is useful for spam detection, disease-risk classification, and customer churn prediction.

## Summary
Learned how Logistic Regression performs classification using probabilities and the sigmoid function, and explored model training and evaluation with Scikit-learn.
