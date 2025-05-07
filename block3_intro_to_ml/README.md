# ![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
# ![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
# ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

# Block 3: Intro to Machine Learning Basics

## Overview
This repository contains a beginner-to-intermediate level machine learning project focused on foundational model development using Python and scikit-learn. The work is part of a structured learning path for becoming a Human-Centered Machine Learning Engineer. It includes regression and classification workflows, model performance evaluation, overfitting exploration, and best practices for notebook presentation and version control.

This block focuses on learning the fundamentals of supervised machine learning.  
I trained my first simple models for **regression** and **classification** using scikit-learn.

The primary goals were understanding how to:
- Identify features and target variables
- Split data into training and validation sets
- Train basic models
- Evaluate model performance using appropriate metrics

## File Structure
```
block3_intro_to_ml/
├── regression_housing.ipynb         # Notebook for housing prices regression
├── classification_titanic.ipynb     # Notebook for Titanic classification
├── README.md                        # Summary README for the block
├── plots/                           # Folder for visualizations
│   ├── housing_model_comparison.png     # Bar chart: Decision Tree vs Linear Regression MAE
│   ├── housing_feature_set_comparison.png # Feature set MAE comparison
│   ├── housing_rf_feature_importance.png # Random Forest feature importances
│   └── titanic_confusion_matrix.png     # Confusion matrix heatmap
│   └── titanic_feature_importance.png   # Random Forest feature importances (Titanic)
└── data/                             # Local copies of datasets
    ├── housing.csv
    └── titanic.csv
    └── titanic_cleaned.csv
```

## Highlights
- Followed a structured 8-day plan to build and refine models with growing complexity and insight.
- Trained a **DecisionTreeRegressor** and calculated MAE to measure performance.
- Trained a **DecisionTreeClassifier** for Titanic survival prediction and calculated accuracy.
- Explored **overfitting and underfitting** by adjusting features.
- Practiced clean workflows: training, validation, evaluation, and documentation.

## Key Takeaways
- **Data Splitting Matters:** Performance differs sharply between training and validation sets, exposing overfitting.
- **Feature Selection Impacts Accuracy:** Including irrelevant or leaking features can inflate metrics incorrectly.
- **Baseline Understanding Built:** Now comfortable fitting first models and interpreting simple evaluation metrics.

## Tools and Libraries Used
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib (optional for visualization)

## Example Git Commands

```bash
# Stage all changes
git add .

# Commit with a clear message
git commit -m "Complete Block 3: Intro to ML basics (regression/classification)"

# Push to GitHub
git push origin main
```

## How to Use

Open each notebook (.ipynb) to view code, explanations, and results.

Each model includes:

- Data loading
- Preprocessing
- Model training
- Model evaluation
- Brief reflections

## License

This project is licensed under the MIT License. See the LICENSE file for details.