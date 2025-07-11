# Day 6: Insight Report

## 1. Objective
Summarize the key takeaways from Block 8's visualizations, focusing on clarity, accuracy, and human-centered communication.

## 2. Key Insights

### Insight 1: False Negatives Exceed False Positives
- The logistic regression model misclassified 9 gallstone-positive patients as negative, compared to 7 false positives.
- While performance is balanced overall, minimizing false negatives may be clinically important.

### Insight 2: Model Slightly Overpredicts 'No Gallstones'
- The grouped bar chart showed the model predicted more “No Gallstones” cases than actually existed.
- This suggests a conservative tendency, which may reduce overdiagnosis but could miss real cases.

### Insight 3: Model Correctly Identified 72% of Gallstone Cases
- In stakeholder terms: the model caught 23 out of 32 patients with gallstones.
- This reinforces the model’s clinical potential and provides a plain-language framing of its value.

## 3. Visual Design Reflection

The charts created in this block followed key principles from *Storytelling with Data*:
- **Insight-first titles** were used to guide interpretation before the reader even saw the visuals.
- **Minimal ink** and deliberate color choices helped direct focus (e.g., using red to highlight false negatives).
- **Contextual clarity** was emphasized by labeling axes, reducing gridlines, and integrating key numbers into the visuals themselves.

These practices improved accessibility for both technical and non-technical audiences, making the results easier to understand and act upon.

## 4. Conclusion

This block demonstrated the importance of visual communication in human-centered machine learning. Visuals not only clarified model performance but also framed it for decision-makers. The ability to create clear, focused, and stakeholder-friendly charts is now a practiced skill ready to be applied in future modeling workflows.