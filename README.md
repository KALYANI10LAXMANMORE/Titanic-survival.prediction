# Titanic-survival.prediction
A machine learning project to predict Titanic passenger survival using feature engineering techniques like Title extraction, Family Size, and Cabin presence. Includes preprocessing pipelines, multiple classification models, evaluation metrics, and feature importance for model explainability.
# Titanic Survival Prediction 🚢

## 📌 Objective
Predict whether a passenger survived using ML models.

## ⚙️ Features Used
- Title (Mr, Mrs, etc.)
- Family Size
- Cabin Presence

## 🤖 Models
- Logistic Regression
- Random Forest
- Gradient Boosting

## 📊 Metrics
- Accuracy
- Precision
- Recall
- F1 Score

## ▶️ How to Run

1. Install libraries:
pip install pandas numpy scikit-learn matplotlib seaborn joblib

2. Run notebook

## 🔮 Prediction Example

import joblib

model = joblib.load("titanic_model.pkl")
prediction = model.predict(sample_data)

print(prediction)
