# The visualizations below have not yet been created—they are planned for future sessions as part of the Block 8 work.
# Day 1: Key Insights Selected for Visualization

As part of Block 8, we are visualizing insights from the Block 5 project: **Gallstone Risk Prediction**. Below are the selected findings that will be translated into explanatory, stakeholder-friendly visualizations.

---

## Insight 1: Logistic Regression Outperforms Random Forest

**Summary:**  
Despite its simplicity, Logistic Regression outperformed Random Forest across all evaluation metrics, including accuracy, recall, and AUC. This supports the use of interpretable models in clinical decision support.

**Planned Visualization:**  
- Bar chart comparing Accuracy, Precision, Recall, F1 Score, and ROC AUC for both models  
- Optionally, ROC curves for both models on the same plot  

**Design Note:**  
- Title will clearly communicate the takeaway (e.g., “LogReg Outperforms RF on All Metrics”)  
- Use color to highlight the stronger model; use neutral tones for others  
- Eliminate clutter (no chart borders or gridlines; direct bar labeling instead of legend)

---

## Insight 2: Vitamin D and CRP Levels Are Top Predictors

**Summary:**  
Features like `vitamin_d_ng_ml` and `crp_mg_l` showed strong predictive power and aligned with clinical risk factors. These were top coefficients in the Logistic Regression model and had strong SHAP values for Random Forest.

**Planned Visualization:**  
- Boxplots of `vitamin_d_ng_ml` and `crp_mg_l` by gallstone status  
- Bar chart of top Logistic Regression coefficients  

**Design Note:**  
- Use aligned boxplots with a consistent scale  
- Apply color sparingly to highlight one key feature per plot  
- Chart titles will state the insight, e.g., “Lower Vitamin D Linked to Gallstones”

---

## Insight 3: False Negatives Are More Costly Than False Positives

**Summary:**  
Logistic Regression produced fewer false negatives, which is crucial in clinical settings. Missing a gallstone diagnosis (false negative) has more severe consequences than a false positive.

**Planned Visualization:**  
- Annotated confusion matrices or bar chart comparing FN/FP rates by model  

**Design Note:**  
- Structure confusion matrix or bar chart to emphasize FN/FP difference  
- Use action-oriented titles: “Fewer False Negatives with Logistic Regression”  
- Highlight the clinically safer model (LogReg) with a distinct color; grey out the rest
