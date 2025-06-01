


# Model Card – Gallstone Risk Prediction

## 1. Overview

This model card documents two machine learning models—**Logistic Regression** and **Random Forest**—developed to predict the likelihood of gallstone disease using bioimpedance and laboratory data. The models are intended to assist clinicians by providing interpretable, data-driven risk assessments that may support early diagnosis and treatment decisions.

---

## 2. Intended Use

These models are designed for use in clinical decision-support tools where early identification of gallstone risk could guide further diagnostics or lifestyle interventions. They are not substitutes for formal diagnosis or imaging studies but may provide useful screening insights in primary care settings.

---

## 3. Data

- **Source**: Derived from the dataset used in *Esen et al. (2024)*, which includes 586 patient records.
- **Features**: Bioimpedance measures (e.g., TBW, ICW, ECF ratios), laboratory test results (e.g., CRP, ALT, Vitamin D), and clinical indicators (e.g., diabetes, hyperlipidemia).
- **Target Variable**: Presence of gallstones, as diagnosed via ultrasound.
- **Preprocessing**:
  - Missing values imputed (median or mode)
  - Outliers handled via z-score and IQR methods
  - Multicollinearity reduced via VIF pruning (for logistic regression)
  - Standardization applied where needed

---

## 4. Models

### Logistic Regression
- **Input**: VIF-pruned and standardized features
- **Strengths**: High interpretability, strong recall
- **Use case**: Clinically transparent tool for risk stratification

### Random Forest
- **Input**: Full feature set
- **Strengths**: Non-linear feature handling, higher CV-AUC
- **Use case**: Supplementary model for complex risk patterns

---

## 5. Performance

| Metric        | Logistic Regression | Random Forest |
|---------------|---------------------|----------------|
| Accuracy      | 0.750               | 0.703          |
| Precision     | 0.767               | 0.724          |
| Recall        | 0.719               | 0.656          |
| F1 Score      | 0.742               | 0.689          |
| ROC AUC       | 0.811               | 0.791          |
| CV AUC (5-fold)| 0.814              | 0.841          |

---

## 6. Interpretability

- **Logistic Regression**: Coefficients clearly show positive/negative associations (e.g., CRP ↑ risk, Vitamin D ↓ risk).
- **Random Forest**: Supported by SHAP, permutation importance, and mean decrease in impurity for transparency.

---

## 7. Ethical Considerations and Limitations

- **Bias Risk**: Data originates from a specific patient population and may not generalize across demographics.
- **Clinical Use**: Should only augment—not replace—medical diagnosis by trained professionals.
- **False Negatives**: Particularly important in this application due to delayed diagnosis risks. Models are tuned to prioritize recall.
- **Transparency**: Logistic Regression favored for explainability; Random Forest interpretability is supplemented via SHAP.

---

## 8. References

Esen İ, Arslan H, Aktürk Esen S, Gülşen M, Kültekin N, Özdemir O. Early prediction of gallstone disease with a machine learning-based method from bioimpedance and laboratory data. *Medicine*. 2024;103:8(e37258). doi: [10.1097/MD.0000000000037258](http://dx.doi.org/10.1097/MD.0000000000037258)