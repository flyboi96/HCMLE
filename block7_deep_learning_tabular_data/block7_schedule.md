# Block 7 Schedule: Deep Learning for Tabular Data

## Overview
This block explores deep learning applied to structured/tabular data. Using fastai's `TabularLearner`, we’ll model a dataset with mixed categorical and continuous features. Emphasis is placed on preprocessing, embedding usage, interpretability, and comparisons with classical ML workflows.

---

## Day-by-Day Plan

### Day 1: Define Block 7 goals and choose Tabular path
- Review Block 7 scope and outcomes  
- Choose Tabular focus
- Set up environment (fast.ai, Colab, or local)  
- Outline 7-day schedule

**Deliverables:**
- Tabular path chosen  
- Environment ready  
- Schedule saved (`block7_schedule.md`)

### Day 2: Preprocess input data
- Load sample tabular dataset (Rossmann, Adult Income, etc.)
- Normalize continuous vars, encode categoricals
- Save preprocessed data in notebook

### Day 3: Define tabular DL model
- Use fastai's `TabularLearner`
- Include embedding layers for categoricals
- Add markdown explaining model architecture

### Day 4: Train and evaluate
- Train with validation split
- Save plots of loss/accuracy over epochs

### Day 5: Evaluate on holdout
- Show predictions on validation set
- Comment on correct/incorrect examples

### Day 6: Interpret model
- Use fastai’s `plot_feature_importance()`
- Describe most influential features

### Day 7: Reflect on classical vs DL
- 5 bullet summary comparing deep learning with classical ML

### Day 8: Final cleanup and deliverables
- Clear outputs, tag `block7_complete`, update README