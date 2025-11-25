# Group_2_IMT574
📊 Lifestyle Machine Learning Project
Calorie Burn Prediction • Health Status Classification • Workout Efficiency Insights

This project explores how basic lifestyle, biometric, and workout-related data can be used to generate meaningful health insights using machine learning. Built as part of IMT 574 — Machine Learning at the University of Washington.

Our analysis is structured around three research questions that together create a full lifestyle analytics pipeline.

🔍 Research Questions
RQ1 — Calorie Burn Prediction (Regression)

Goal: Predict calories burned during a workout based on biometric + workout metrics.
Model Used: Random Forest Regressor

Key Insight:
Workout type and session duration are the strongest drivers of energy expenditure—more than gender or age.

RQ2 — Health Status Classification (Multiclass)

Goal: Classify individuals into Fit, Moderate, or At-Risk based on lifestyle indicators.
Models Used:

Logistic Regression

Decision Tree

Metrics:

Accuracy

Macro F1-Score

Confusion Matrix

Key Insight:
Lifestyle variables like BMI, hydration, workout frequency, and calorie intake are strong indicators of general health.

RQ3 — Workout Efficiency Analysis

Goal: Identify which factors most strongly influence workout effectiveness and consistency.
Methods Used:

Random Forest Regression

Key Insight:
Higher-intensity workouts (HIIT, Strength Training) yield higher calorie efficiency, even when controlling for body composition.

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

SHAP Explainability


📈 Key Visualizations

Correlation heatmap

Actual vs Predicted Calories

SHAP summary for calorie model

Confusion matrices for health classification

Feature importance charts


📘 Course

IMT 574 — Machine Learning
Information School, University of Washington
Professor Sophin Liu (Fall 2025)

⭐ Summary

This project demonstrates that machine learning can effectively model calorie burn, classify health status, and extract meaningful workout insights using only basic demographic and lifestyle data. The findings reinforce the growing value of data-driven approaches in personal health analytics and digital well-being.
