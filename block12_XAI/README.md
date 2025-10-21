

# Block 12 – Explainable AI Techniques

## Overview

Block 12 explores hands-on tools and concepts for Explainable AI (XAI), a crucial pillar of Human-Centered Machine Learning Engineering (HCMLE). This block focuses on understanding and applying key interpretability methods such as:

- **SHAP** (SHapley Additive exPlanations)
- **LIME** (Local Interpretable Model-Agnostic Explanations)
- **Permutation Importance**
- **Partial Dependence Plots (PDPs)**

Each tool was implemented on a working ML model, with results interpreted, visualized, and documented for both technical and non-technical audiences.

---

## Objectives

- Learn and apply local and global explainability tools
- Compare interpretability methods in terms of theory and practical usability
- Translate technical model behavior into understandable insights
- Build habits for clear, professional documentation of explainability pipelines

---

## Folder Structure

```
block12_XAI/
│
├── notebooks/              # Daily Jupyter Notebooks
├── plots/                  # All generated visuals
│   └── summary/            # Final visuals for reports
├── models/                 # Trained model artifacts
├── data/                   # Input datasets
├── block12_schedule.md     # Daily session plan
├── model_card.md           # Model metadata and evaluation
├── data_dictionary.md      # Feature definitions and context
├── notes_success_criteria.md # Completion definitions
├── README.md               # This file
```

---

## Deliverables

- SHAP explanations with visualizations for individual predictions
- LIME explanations for instance-based local interpretability
- Permutation importance and PDP for global model insight
- Comparison summary of SHAP, LIME, and global methods
- User-facing natural language explanation of a prediction
- Full professional documentation (README, model card, data dictionary)

---

## Highlight Plots

Key visuals (e.g., SHAP bar chart, PDP curves) saved in:

`/plots/summary/`

Use these to build future UX or decision-support interfaces.

---

## Completion Criteria

See [`notes_success_criteria.md`](./notes_success_criteria.md) for what defines a “complete” session and block in this project.

---

## Next Steps

- Extend SHAP to time-series or NLP model
- Explore counterfactual explanation libraries
- Begin designing UI for communicating model decisions to real users

---

## Related Docs

- [`model_card.md`](./model_card.md)  
- [`data_dictionary.md`](./data_dictionary.md)  
- [`block12_schedule.md`](./block12_schedule.md)