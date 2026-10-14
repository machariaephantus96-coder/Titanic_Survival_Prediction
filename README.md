# Titanic Survival Prediction

A machine learning project that predicts whether a passenger survived the Titanic disaster, using the Kaggle Titanic dataset (891 passengers).

## What the project does

- **Cleans the data:** drops `Cabin` (77% missing) and ID columns, and fills missing `Age` and `Embarked` values.
- **Builds a preprocessing pipeline:** scales the numeric features and one-hot encodes the categorical ones, so the test data never leaks into training.
- **Compares five models** with 5-fold cross-validation: Logistic Regression, KNN, SVM, Random Forest and Gradient Boosting.
- **Tunes the Random Forest** with Grid Search, Randomized Search and Optuna.
- **Evaluates the final model** on a held-out test set, reaching **81% accuracy**.
- **Saves the full pipeline** with joblib, so raw passenger data can be passed in for predictions.

## Tools

Python, pandas, scikit-learn, Optuna, seaborn, matplotlib

## Author

Ephantus Macharia aspiring data analyst, Nairobi, Kenya
