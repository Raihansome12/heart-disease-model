# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Overview

This project explores and predicts heart disease using clinical data. It covers the full machine learning workflow including data exploration, visualization, model training, evaluation, and interpretation.

---

## 📊 Exploratory Data Analysis (EDA)

Performed analysis to understand the dataset:

* Distribution of target variable
* Relationship between sex and heart disease
* Age vs maximum heart rate visualization
* Correlation heatmap of features

---

## ⚙️ Models Used

* Logistic Regression
* Random Forest Classifier

Models were trained and compared to evaluate performance.

---

## 🔍 Hyperparameter Tuning

Used RandomizedSearchCV to optimize model performance:

* Logistic Regression: tuned regularization parameter (C)
* Random Forest: tuned tree depth, number of estimators, and splitting criteria

---

## 📈 Model Evaluation

* Accuracy score
* ROC Curve analysis
* AUC Score (~0.92)

---

## 🧠 Key Insights

* Chest pain type (cp) is the strongest predictor
* ECG-related features (slope, restecg) significantly influence predictions
* Some features like cholesterol and age showed lower importance in this dataset

---

## ⚠️ Important Note

Feature importance is model-dependent and reflects how the model uses features, not necessarily real-world causality.

---

## 🚀 Future Improvements

* Apply SHAP for better interpretability
* Test advanced models (XGBoost, LightGBM)
* Deploy as a web application (Streamlit)
