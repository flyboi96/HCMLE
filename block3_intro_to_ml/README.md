# Block 3: Intro to Machine Learning Basics

## Overview
This block focuses on learning the fundamentals of supervised machine learning.  
I trained my first simple models for **regression** and **classification** using scikit-learn.

The primary goals were understanding how to:
- Identify features and target variables
- Split data into training and validation sets
- Train basic models
- Evaluate model performance using appropriate metrics

## Contents

| File | Description |
|:---|:---|
| `regression_housing.ipynb` | Predicts housing prices using a basic regression model. Calculates Mean Absolute Error (MAE). |
| `classification_titanic.ipynb` | Predicts Titanic survival using a decision tree classifier. Calculates model accuracy. |
| `plots/` | (Optional) Folder containing any relevant figures or visualizations. |
| `README.md` | This summary document for Block 3. |

## Highlights
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

## How to Use

Open each notebook (.ipynb) to view code, explanations, and results.

ach model includes:

- Data loading
- Preprocessing
- Model training
- Model evaluation
- Brief reflections