💻 Laptop Price & Category Prediction

End-to-End Machine Learning System (Regression + Classification)

📌 Project Overview

This project is a complete supervised machine learning system built to:

Predict laptop prices using regression models

Classify laptops into Budget, Mid, and Premium categories

Compare multiple algorithms and evaluate performance

Analyze feature importance for interpretability

Understand real-world ML pipeline challenges

🎯 Objectives

Build a regression model to predict laptop prices

Convert the problem into a classification task

Compare Linear Regression, Random Forest, and XGBoost

Evaluate models using proper metrics

Interpret feature importance

Understand overfitting and generalization

📊 Dataset Description

The dataset contains 823 laptop records with the following features:

Brand

Processor brand and name

Processor generation

RAM (GB) and RAM type

SSD and HDD storage

Operating system and OS bit

Graphics card (GB)

Weight

Warranty

Touchscreen availability

MS Office availability

Rating

Number of ratings

Number of reviews

Target variable: Price

🛠️ Machine Learning Workflow
1️⃣ Data Preprocessing

Cleaned and converted data types

Encoded categorical variables using OneHotEncoder

Structured preprocessing using ColumnTransformer

Built reproducible pipelines

2️⃣ Regression Models (Price Prediction)

Models implemented:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Evaluation metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

XGBoost achieved the best performance due to its ability to handle non-linear relationships and feature interactions effectively.

3️⃣ Classification Extension (Budget / Mid / Premium)

Converted the price prediction problem into a classification task.

Models implemented:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Evaluation metrics:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

This helped reinforce the practical difference between regression and classification.

🔍 Feature Importance Insights

Key observations from feature importance analysis:

SSD size strongly influences laptop price

RAM significantly impacts price category

Graphics card memory affects premium classification

Processor type plays a critical role

Ratings and reviews have moderate influence

🧠 Key Learnings

This project helped me deeply understand:

How .fit() and .predict() work internally

How models learn patterns from features

The difference between regression and classification

Why feature engineering matters

How overfitting affects model performance

How hyperparameter tuning works

Why deployment pipelines must match training pipelines

How model evaluation metrics differ by task

🚧 Deployment Challenges Faced

While attempting deployment, I encountered:

Feature shape mismatch errors

ColumnTransformer inconsistencies

Inference-time preprocessing alignment issues

These challenges improved my understanding of real-world ML system robustness.

🧰 Technologies Used

Python

Pandas

NumPy

Scikit-learn

XGBoost

Matplotlib

Jupyter Notebook

📈 Future Improvements

Implement SHAP for advanced explainability

Add cross-validation enhancements

Create production-ready API deployment

Extend into recommendation system

🏆 Final Reflection

This project strengthened my foundation in supervised learning by helping me move beyond running algorithms to understanding how machine learning systems behave in practice, how models fail, and how to build structured pipelines like an engineer.
