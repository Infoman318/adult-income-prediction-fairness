# Results

This folder contains the evaluation outputs generated during the machine learning pipeline.

## Contents

### `model_performance.csv`

A summary of the performance of all evaluated machine learning models on the Adult Census Income dataset.

The following evaluation metrics are included:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

The models compared in this project are:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting
- XGBoost
- Tuned Random Forest (GridSearchCV)

## Purpose

These files allow users to review the experimental results without rerunning the notebook. They also make it easier to compare model performance and reproduce the analysis.

The visualizations corresponding to these results (ROC Curve, Confusion Matrix, Feature Importance, and Model Comparison) are available in the `images/` directory.
