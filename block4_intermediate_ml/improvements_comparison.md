# 📈 Model Improvement Summary — Block 4

This report documents the progressive improvement of a housing price prediction model through structured experimentation and pipeline optimization. The comparison spans from an initial baseline linear model to a tuned Random Forest evaluated on a hold-out test set.

---

## 🔁 Before vs. After: Performance Metrics

| Model                               | MAE (AUD)     | RMSE (AUD)    | R² Score |
|------------------------------------|---------------|---------------|----------|
| Baseline (Block 3: Linear Model)   | \$262,179     | N/A           | ~0.59    |
| Basic Decision Tree                | \$162,179     | N/A           | ~0.72    |
| Cross-Validated Pipeline (Day 5)   | \$136,392     | \$247,778     | 0.850    |
| Tuned Model (CV Mean, Day 6)       | \$136,362     | N/A           | N/A      |
| **Final Hold-Out Model (Day 7)**   | **\$135,083** | **\$234,516** | **0.862** |

> 📌 Note: Final evaluation conducted on a hold-out test set (20%) to validate generalization.

---

## 📊 Improvements by Phase

### 📌 Block 3 → Block 4 Day 1–2
- Replaced naive row-dropping with a proper preprocessing pipeline.
- Imputed missing values using statistical strategies.
- Introduced encoding for categorical variables via `OneHotEncoder`.

### 📌 Day 3–4
- Built scikit-learn pipelines with `ColumnTransformer` for modularity.
- Engineered domain-specific features:
  - `TotalRooms` (sum of bedrooms, bathrooms, and rooms)
  - `HouseAge` (2025 - YearBuilt)
  - `PricePerSqm` (for analysis)

### 📌 Day 5–6
- Switched to **Random Forest Regressor** for non-linear modeling.
- Introduced robust evaluation: `MAE`, `RMSE`, `R²` via 5-fold CV.
- Tuned hyperparameters (`max_depth`, `n_estimators`) via `GridSearchCV`.

### 📌 Day 7
- Trained best model on full data and evaluated on unseen hold-out set.
- Achieved lowest MAE and RMSE while maintaining high R².

---

## 🧠 Key Learnings

- **Feature engineering** had the single biggest impact on reducing error (~\$100K MAE drop).
- **Cross-validation** and **model tuning** further reduced error and stabilized predictions.
- **Ensemble methods** significantly outperformed linear baselines, especially in non-linear data regimes.

---

## 🧰 Final Model Artifacts

- ✅ `final_model.ipynb`: End-to-end notebook with training and evaluation
- ✅ `model_tuning.ipynb`: Grid search tuning and diagnostics
- ✅ `model_evaluation.ipynb`: Metric visualizations and interpretation
- ✅ `feature_engineering.ipynb`: Feature construction pipeline

---

## ✅ Conclusion

Block 4 successfully demonstrated how methodical ML development—focusing on **pipelines**, **evaluation**, **feature engineering**, and **tuning**—can yield high-performance, production-ready models. The lessons and techniques in this block are foundational to human-centered machine learning engineering and real-world deployable systems.