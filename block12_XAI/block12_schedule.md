

# Block 12: Explainable AI Techniques (Weeks 23–24)

## 1. Objective

Deepen practical skills in model interpretability and explainable AI (XAI). Apply popular tools such as SHAP, LIME, PDP, and permutation importance to analyze model predictions. Focus on generating technical explanations that can be translated into user-friendly insights.

---

## 2. Schedule Overview

Each session is designed for ~1 hour of focused work. Commit messages follow Conventional Commit format. Tags are applied at the end of each session. Code and documentation should be clean, professional, and stored in the appropriate folders (`notebooks/`, `plots/`, `models/`, `data/`).

---

### **Day 1 – Define Block Goals and Setup**

- **Objective**: Define Block 12 scope and prepare workspace
- **Deliverables**:
  - `block12_schedule.md` created
  - Repository structure initialized
- **Tasks**:
  - Review focus, resources, and outputs
  - Create schedule in this file
  - Initialize folders and notebook template
  - Commit: `chore(config): initialize block12 structure`
  - Tag: `day1_scope_complete`

---

### **Day 2 – Global Explainability Methods (PDP & Permutation Importance)**

- **Objective**: Understand and implement global interpretability techniques
- **Deliverables**:
  - Permutation importance + PDP visualizations
  - Interpretations written in markdown
- **Tasks**:
  - Complete relevant sections of Kaggle Explainability
  - Apply to a small model (or previous one)
  - Commit: `feat(viz): add permutation importance and PDP`
  - Tag: `day2_globalmethods_complete`

---

### **Day 3 – SHAP Implementation and Analysis**

- **Objective**: Use SHAP to explain individual predictions
- **Deliverables**:
  - SHAP summary + instance-level plot
  - Written explanation of SHAP values
- **Tasks**:
  - Read SHAP docs and DataCamp article
  - Apply SHAP to tree-based model
  - Commit: `feat(shap): shap explanations and interpretation`
  - Tag: `day3_shap_complete`

---

### **Day 4 – LIME Implementation and Analysis**

- **Objective**: Use LIME to explain model behavior
- **Deliverables**:
  - LIME output visualized
  - Explanation written for one instance
- **Tasks**:
  - Read Molnar's LIME chapter
  - Apply LIME to classifier
  - Commit: `feat(lime): lime explanations for model decision`
  - Tag: `day4_lime_complete`

---

### **Day 5 – Compare SHAP, LIME, and PDP**

- **Objective**: Summarize differences between explainability methods
- **Deliverables**:
  - Comparison bullet list or table
- **Tasks**:
  - Reflect on tradeoffs: SHAP vs LIME vs PDP
  - Commit: `docs(interpret): add XAI method comparison`
  - Tag: `day5_compare_complete`

---

### **Day 6 – User-facing Explanation Report**

- **Objective**: Create plain-language explanation of a prediction
- **Deliverables**:
  - Explanation with 3 ranked features + natural language
- **Tasks**:
  - Choose a model prediction
  - Use SHAP or LIME to generate explanation
  - Commit: `docs(report): add prediction explanation write-up`
  - Tag: `day6_explanation_complete`

---

### **Day 7 – Professional Documentation**

- **Objective**: Update block documentation with technical artifacts
- **Deliverables**:
  - `README.md`, `model_card.md`, `notes_success_criteria.md`
- **Tasks**:
  - Document methods, results, and insights
  - Commit: `docs(docs): update XAI documentation`
  - Tag: `day7_docs_complete`

---

### **Day 8 – Reflection and Release**

- **Objective**: Conclude Block 12 with final thoughts and next steps
- **Deliverables**:
  - `Day8_reflection.md` completed
  - Tag `block12_complete` created
- **Tasks**:
  - Write final reflection
  - Add "Next Steps" to `README.md`
  - Commit: `release(block): finalize Block 12`
  - Tag: `block12_complete`

---

## 3. Notes on ChatGPT Use

**Use ChatGPT for:**
- Interpreting SHAP/LIME outputs in natural language
- Comparing tools and refining your summaries
- Rewording or proofreading explanations and documentation

**Don’t use ChatGPT for:**
- Writing code for SHAP, LIME, or PDP
- Generating explanations or analysis without doing the work
- Skipping readings or relying on AI to replace hands-on learning

---

## 4. Folder Structure

```
block12_XAI/
│
├── notebooks/
├── plots/
│   └── summary/
├── models/
├── data/
├── block12_schedule.md
├── model_card.md
├── data_dictionary.md
├── notes_success_criteria.md
├── README.md
```

---

## 5. Commit Format

All commits must follow:

```
<type>(<scope>): <message>
```

Example: `feat(shap): add shap explanation to model notebook`

---

Ready to begin Day 1. Schedule saved in `block12_schedule.md`.