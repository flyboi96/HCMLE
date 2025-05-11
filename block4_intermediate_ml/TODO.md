# ✅ Block 4 TODO List
Human-Centered Machine Learning Engineer Journey  
Focus: Intermediate Modeling, Pipelines, and Evaluation

---

## 🔧 Feature Engineering Ideas

- [ ] Combine `Rooms`, `Bedroom2`, and `Bathroom` into `TotalRooms`
- [ ] Create `Price_per_sqm` using `BuildingArea`
- [ ] Convert `YearBuilt` to `Age` (e.g., 2025 - YearBuilt)
- [ ] Bin `Distance` into proximity tiers (e.g., inner-city, mid-range, outer)
- [ ] Flag modern homes: `Is_Modern = YearBuilt > 2000`

---

## 🔄 Preprocessing / Pipeline Design

- [ ] Use `SimpleImputer` for low-missing numeric features (`Car`)
- [ ] Drop or median-impute `BuildingArea` (evaluate trade-offs)
- [ ] Apply `OneHotEncoder` or frequency encoding for high-cardinality categoricals (`Suburb`, `CouncilArea`)
- [ ] Use `ColumnTransformer` to combine numerical/categorical flows
- [ ] Create a full pipeline with preprocessing + modeling

---

## 🤖 Modeling Plan

- [ ] Baseline: Decision Tree Regressor (no tuning)
- [ ] Main: Random Forest Regressor (default, then tuned)
- [ ] Explore gradient boosting (optional)

---

## 🧪 Validation Strategy

- [ ] Use `train_test_split` for quick initial experiments
- [ ] Apply `cross_val_score` for more reliable results
- [ ] Run `GridSearchCV` for tuning (e.g., `max_depth`, `n_estimators`)
- [ ] Track and compare MAE, RMSE, R² for each model

---

## 📊 Reporting / Output

- [ ] Save visualizations to `plots/` (feature importances, tuning curves)
- [ ] Summarize model performance in `improvement_comparison.md`
- [ ] Track experiment notes in markdown cells or comments

---

## ❓ Questions to Explore

- Does adding `BuildingArea` (even with imputation) improve accuracy?
- What encoding works best for `Suburb`?
- Is log-transformation of `Price` helpful for tree-based models?
- How much variance does feature engineering actually explain?

---

🧠 This file evolves during Block 4 to guide ideas, experiments, and next steps.