
# 🧠 Project Proposal – Gallstone Prediction

## 1. What is the problem?

This project aims to develop a machine learning model that predicts the presence of gallstone disease using demographic, bioimpedance, and laboratory data. The dataset is sourced from a 2024 study conducted at Ankara VM Medical Park Hospital and includes 320 patients, with 161 diagnosed with gallstones. The goal is to use readily available non-imaging features to accurately identify individuals who are likely to have gallstone disease.

## 2. Who is the user/stakeholder?

The primary stakeholders are internal medicine physicians and general practitioners who often serve as the first point of contact for patients experiencing abdominal discomfort. These clinicians must decide which patients should be referred for further diagnostic imaging. Secondary users could include hospital administrators seeking to reduce imaging costs, or healthcare researchers interested in non-invasive diagnostic tools.

## 3. What does success look like?

A successful model will:
- Achieve an AUC-ROC score of at least 0.85 on hold-out data
- Maintain sensitivity (recall for positive cases) ≥ 90%, minimizing false negatives
- Use interpretable features so clinicians can understand and trust the predictions
- Be robust to demographic variation (e.g., age, sex)

Technical success means the model generalizes well; practical success means it supports better triage decisions in a clinical setting.

## 4. Why does it matter?

Gallstones affect a large portion of the adult population and can lead to serious complications like biliary colic or pancreatitis. However, diagnosis typically requires imaging (ultrasound or CT), which is costly and not always available in resource-limited settings. A machine learning model that uses inexpensive, non-invasive measurements could:
- Help prioritize high-risk patients for imaging
- Reduce unnecessary imaging referrals
- Improve early detection and treatment outcomes

Ultimately, this model can make care more proactive, equitable, and cost-effective.

---

**Citation:**  
Esen, I., Arslan, H., Aktürk, S., Gülşen, M., Kültekin, N., & Özdemir, O. (2024). Gallstone [Dataset]. UCI Machine Learning Repository. https://doi.org/10.1097/md.0000000000037258
