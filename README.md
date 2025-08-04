# Comparative-Analysis-of-Machine-Learning-Models-for-Heart-Disease-Risk
This project delivers a comparative analysis of machine‑learning models for predicting cardiovascular disease from clinical and lifestyle variables. It benchmarks several classifiers, employs Mutual Feature Selection to select the most informative features, and contrasts each model’s predictive performance both before and after feature selection.
# Dataset Analysis
The dataset contains patient health-related information including:

* Age, gender, blood pressure, cholesterol, glucose levels
* Lifestyle indicators: smoking, alcohol intake, physical activity
* Medical history indicators
Target Variable: Presence of cardiovascular disease (binary classification)

# Models Tested
✅ K-Nearest Neighbors (KNN)
✅ Naive Bayes
✅ Logistic Regression
✅ Decision Tree
✅ Random Forest
✅ Support Vector Machine (SVM)
✅ XGBoost
✅ Stacking (Meta Ensemble)

# Conclusion
* Ensembles Lead the Scoreboard: Combined learners—especially Random Forest and the Stacked meta-model—reliably eclipsed every stand-alone algorithm, delivering the highest marks in accuracy, precision, recall, F1, and ROC-AUC.
* Mutual-Information Filters Boost Robustness: Selecting predictors via mutual information produced a well-balanced feature set, curbing over-fitting and sharpening interpretability while keeping performance uniformly strong across metrics.
* Chi-Square Filters: Great for Categories, Less for Non-Linear Nuance: The Chi-Square approach excelled with models that favor linear, categorical relationships, posting impressive accuracy. Yet it trimmed away some interactions that non-linear methods (e.g., SVM) exploit, slightly capping their potential.
