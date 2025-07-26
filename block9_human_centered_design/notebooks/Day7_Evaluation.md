# Day 7: Usability Evaluation of Prototype

## 1. Method
- **Technique Used**: Heuristic evaluation and simulated walkthrough
- **Evaluator**: Self-assessment based on Nielsen’s usability heuristics

---

## 2. Context Recap
- **Prototype Evaluated**: AI content recommender user flow (from Day 6)
- **Scenario**: User opens app to browse curated movie recommendations, uses filter, clicks for info, saves to watchlist

---

## 3. Evaluation Findings

| Heuristic | Observation | Strength/Weakness | Suggested Change |
|-----------|-------------|-------------------|------------------|
| Visibility of system status | Filter results update without confirmation | Weakness | Add small loading spinner or update confirmation |
| Match between system & real world | Uses icons with clear labels ("Save", "More Info") | Strength | Retain icon-text pairs for clarity |
| User control and freedom | No undo option after saving to watchlist | Weakness | Add “Undo” snackbar after action |
| Consistency & standards | Navigation bar consistent with app conventions | Strength | Maintain standard layout |
| Recognition rather than recall | Cards display movie title, genre, rating | Strength | Continue surfacing key info upfront |

---

## 4. Summary & Reflection
- The prototype largely follows good usability heuristics, especially around visual clarity and recognition.
- However, a lack of immediate feedback and undo features may frustrate users and should be addressed.
- Next steps: If this were a live prototype, a real user testing session would validate assumptions and uncover deeper friction points.