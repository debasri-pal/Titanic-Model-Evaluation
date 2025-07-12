# Titanic Model Evaluation 🚢

This project performs machine learning model evaluation and hyperparameter tuning on the Titanic dataset.

## 🔍 Goal
To train and compare different machine learning models on the Titanic dataset, and optimize the best model using RandomizedSearchCV.

## 🧰 Models Used
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

## 🧪 Evaluation Metrics
Models are compared based on:
- Accuracy
- Precision
- Recall
- F1-score

## 🛠️ Hyperparameter Tuning
Random Forest was tuned using `RandomizedSearchCV`:
```python
{
  'n_estimators': 150,
  'min_samples_split': 5,
  'min_samples_leaf': 1,
  'max_depth': 6,
  'bootstrap': True
}
