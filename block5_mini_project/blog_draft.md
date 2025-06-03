


# From Data to Diagnosis: Building a Transparent Gallstone Risk Model with Machine Learning

Over the course of Block 5 in the HCMLE curriculum, I tackled a real-world classification problem: predicting the presence of gallstones using a mix of clinical labs, body composition metrics, and patient metadata. My goal was not just accuracy, but explainability—critical for any machine learning solution in healthcare.

## Problem & Dataset

I used the publicly available dataset from Esen et al. (2024), which included demographic, laboratory, and bioimpedance measurements from 319 patients. The target variable was binary: presence or absence of gallstones. The dataset was clean, balanced (50.5% positive), and rich in physiological relevance.

## Exploratory Data Analysis (EDA)

Using visual and statistical exploration, I examined trends and validated feature integrity. CRP, Vitamin D, HDL, BMI, and fat-related metrics emerged as potential predictors. I also addressed outliers in features like `obesity_percent` and visualized feature-class relationships using KDE plots, boxplots, and correlation matrices—all stored in `../plots/`.

## Modeling Approach

I trained two baseline models:
- **Logistic Regression**, using VIF-pruned and standardized features
- **Random Forest**, using the full feature set

Both models were evaluated using test set metrics and 5-fold cross-validation. Logistic Regression outperformed Random Forest on all test metrics, including ROC AUC (0.811 vs. 0.791), while Random Forest performed slightly better in cross-validation.

## Evaluation & Interpretation

I used confusion matrices, ROC curves, and a score summary table to compare models. Logistic Regression was not only more accurate, but also more interpretable. I then interpreted model behavior:
- **Logistic Regression**: Used coefficients to explain global feature impact
- **Random Forest**: Applied SHAP, MDI, and permutation importance to visualize and compare top predictors

Across both models, `crp_mg_l` (inflammation), `vitamin_d_ng_ml` (nutrition), and `alt_u_l` (liver function) consistently ranked high—supporting their clinical validity.

## Key Takeaways

- Simpler models like Logistic Regression can outperform complex ones in low-sample, high-signal domains—especially when interpretability is essential.
- SHAP and permutation importance can demystify black-box models, offering complementary insights.
- Visual storytelling principles (e.g., reducing clutter, guiding attention) significantly improve communication of results.

## What I’d Do Differently

With more time, I would:
- Tune hyperparameters for Random Forest
- Explore more interpretable nonlinear models (e.g., GAMs)
- Build a minimal UI to deliver predictions and confidence intervals to clinicians

## Final Thoughts

This project reinforced the value of **transparency**, **clinical context**, and **human-centered design** in machine learning for healthcare. My final deliverables (models, visuals, notebook, and model card) are all committed in a reproducible GitHub repo, tagged under `block5_complete`.

---
**Dataset**: Esen et al. (2024), *Medicine*, [doi:10.1097/MD.0000000000037258](https://doi.org/10.1097/MD.0000000000037258)