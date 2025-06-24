# Model Card: Block 7 Tabular Sales Predictor (Rossmann Dataset)

## Model Overview
This model predicts daily sales revenue for Rossmann retail stores using a deep learning approach trained on historical store and promotional data. It was built with fastai’s `TabularLearner`.

- **Problem Type:** Regression
- **Target Variable:** `Sales`
- **Input Features:** Date-derived variables, store metadata, promotions, and holiday indicators
- **Architecture:** 2-layer fully connected network with categorical embeddings
- **Framework:** fastai v2.7.17 (built on PyTorch)

---

## Data Used
- **Source:** Rossmann Store Sales (Kaggle)
- **Train Size:** ~1M rows
- **Validation Split:** Random 80/20
- **Key Features:**
  - Categorical: `StoreType`, `Promo2`, `StateHoliday`, etc.
  - Continuous: `Customers`, `CompetitionDistance`, etc.
  - Date-derived: `Year`, `Month`, `Week`, `Dayofweek`, etc.

---

## Performance
- **Metric:** RMSE (Root Mean Squared Error)
- **Training RMSE:** Lower and consistent
- **Validation RMSE:** Higher, indicating overfitting

---

## Risks & Limitations
- High variance between train/val loss may signal:
  - Temporal leakage or store-specific overfitting
  - Inadequate representation of validation data
- Model does not account for seasonality or price changes beyond what's encoded
- Performance may degrade on stores not seen during training

---

## Recommended Use
- Internal forecasting and simulation under similar data distribution
- Not suitable for production without further regularization, testing, and explainability analysis