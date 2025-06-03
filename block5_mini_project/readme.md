# Block 5: Mini Project 1 – Gallstone Disease Prediction

This repository contains the work completed during Block 5 of the HCMLE learning roadmap. The goal of this block was to conduct an end-to-end machine learning project that applies concepts learned in previous blocks and produces a human-centered, interpretable solution. The project focuses on predicting gallstone disease based on demographic, laboratory, and bioimpedance data.

---

## Project Summary

**Project Title:** Predicting Gallstone Disease from Non-Imaging Data  
**Dataset:** [Gallstone Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/1150/gallstone-1)  
**Source Paper:** Esen et al. (2024) – DOI: [10.1097/md.0000000000037258](https://doi.org/10.1097/md.0000000000037258)

**Problem:**  
Diagnosing gallstones typically requires imaging, which is costly and resource-intensive. The objective of this project is to build a machine learning classifier that uses accessible, non-imaging data to predict whether a patient is likely to have gallstone disease.

**Stakeholder:**  
Internal medicine physicians and general practitioners who must triage patients for further imaging.

---

## Block Objectives

- Select and define a real-world ML problem
- Load and preprocess clinical tabular data
- Perform EDA and generate meaningful visualizations
- Train, compare, and interpret multiple ML models
- Evaluate with relevant metrics (AUC, recall, etc.)
- Document findings in a clear, professional format
- Reflect on human-centered implications

---

## Folder Structure

```
block5_mini_project/
│
├── data/                # Raw and cleaned data files
├── data_dictionary.md        # Description of features in the dataset
├── notes_success_criteria.md # Planning notes and success metrics
├── notebooks/           # Daily Jupyter notebooks
├── plots/               # Visualizations from EDA and modeling
├── models/              # Serialized model objects
├── reports/             # Final notebook (HTML), model card, blog write-up
├── project_proposal.md  # Project framing document
├── project_schedule.md  # Full 8-day roadmap
├── readme.md            # This file
```

---

## Deliverables

- Cleaned dataset (`cleaned.csv`)
- Full EDA and feature insight notebook
- Two trained models with evaluation metrics
- Model interpretation (SHAP or feature importance)
- Polished notebook with introduction, results, and conclusions
- Model Card (`model_card.md`)
- Blog-style summary (`blog_draft.md`)
- GitHub-tagged release at the end of Day 8
- Data Dictionary (`data_dictionary.md`)
- Success Criteria Notes (`notes_success_criteria.md`)

---

## Key Readings

- **People + AI Guidebook**: User Needs, Mental Models, Explainability
- **Storytelling with Data (Knaflic)**: Chapters on visual clarity, narrative, and user context

---

## Status

Block 5 is currently **in progress**. Stay tuned for daily commits and updates.
