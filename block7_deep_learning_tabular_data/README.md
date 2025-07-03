


# Block 7: Deep Learning for Tabular Data

## Overview
This block explores how deep learning techniques can be applied to structured/tabular datasets using the `fastai` library. You will build, train, and interpret a neural network on a real-world tabular dataset, with an emphasis on preprocessing, model explainability, and comparison to classical ML methods.

---

## Objectives
- Learn how `TabularLearner` works in fastai
- Handle categorical and continuous variables effectively
- Apply data preprocessing (normalization, embeddings)
- Train and evaluate a tabular deep learning model
- Analyze feature importance for interpretability
- Reflect on differences between deep learning and classical ML

---

## Daily Breakdown

| Day | Focus                                               | Deliverables                                               |
|-----|------------------------------------------------------|------------------------------------------------------------|
| 1   | Define scope, choose Tabular path, set up environment| `block7_schedule.md`, environment setup                    |
| 2   | Preprocess tabular dataset                          | Notebook with cleaned and encoded data                     |
| 3   | Define model architecture                           | Model with embedding layers, markdown explanations         |
| 4   | Train model and evaluate                            | Training plots, saved model (`models/block7_model.pkl`)    |
| 5   | Test on holdout set                                 | Predictions + commentary in notebook                       |
| 6   | Interpret model results                             | Feature importance chart, discussion                       |
| 7   | Reflect on DL vs classical ML                       | `block7_reflection.md` with bullet summary                 |
| 8   | Final cleanup and documentation                     | Clean notebooks, commit/tag, updated `README.md`           |

| Day | Focus                               | Deliverables                                               |
|-----|--------------------------------------|------------------------------------------------------------|
| 1   | Define scope, choose path            | [`block7_schedule.md`](./block7_schedule.md)               |
| 2   | Preprocess tabular dataset          | [`day2_preprocessing.ipynb`](./notebooks/day2_preprocessing.ipynb) |
| 3   | Define model architecture           | [`day3_model.ipynb`](./notebooks/day3_model.ipynb)         |
| 4   | Train model and evaluate            | [`day4_train.ipynb`](./notebooks/day4_train.ipynb), [`block7_model.pkl`](./models/block7_model.pkl) |
| 5   | Test on holdout set                 | [`day5_model_evaluation.ipynb`](./notebooks/day5_model_evaluation.ipynb) |
| 6   | Interpret model results             | [`day6_feature_importance.ipynb`](./notebooks/day6_feature_importance.ipynb), `plots/` |
| 7   | Reflect on DL vs classical ML       | [`block7_reflection.md`](./block7_reflection.md)           |
| 8   | Final cleanup and documentation     | Cleaned notebooks, Git tag `day8_complete`, this README    |

---

## Directory Structure

```
block7_deep_learning_tabular_data/
├── notebooks/                # Jupyter Notebooks for each day
├── data/                     # Input datasets
├── models/                   # Saved model files (.pkl)
├── plots/                    # Generated plots and visuals
├── README.md                 # This file
├── block7_schedule.md        # 8-day schedule outline
├── data_dictionary.md        # Descriptions of features used
├── notes_success_criteria.md # Completion criteria for the block
├── block7_reflection.md      # Final reflection on the block
```

---

## Final Model Performance

- **Validation RMSE:** 511.17
- **Model type:** Tabular Neural Network (fastai)
- **Top predictors (drop-column importance):** Customers, Promo, Month, CompetitionDistance

---

## Interpretability Artifacts

- [Permutation Feature Importance](./plots/permutation_feature_importance.png)
- [Partial Dependence - Customers](./plots/pdp_customers.png)
- [SHAP Summary Plot](./plots/shap_tree_summary.png)
- [Embeddings - StoreType](./plots/embedding_storetype.png)

---

## Resources Used

- [fastai Tabular Documentation](https://docs.fast.ai/tabular.core.html)
- [Rossmann Store Sales Dataset (Kaggle)](https://www.kaggle.com/competitions/rossmann-store-sales)
- Optional: [fastbook (Ch. 8)](https://github.com/fastai/fastbook/blob/master/08_collab.ipynb)

---

## Tags
`deep learning` `fastai` `tabular data` `embeddings` `explainability` `HCMLE`