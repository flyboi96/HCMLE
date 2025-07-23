# Day 6: Learn How to Build Simple Prototypes and User Flows

## Intellipaat Video: 07:45:04–08:24:23  
**Topic:** Brainstorming, Mapping, Ideation, and Problem-Solving

---

### 1. Define the Problem First

- Before designing anything, **frame the user problem**: What is the user trying to accomplish? What’s blocking them?
- Ask:  
  > “What specific problem is this screen or flow supposed to solve?”  
  > “What’s the minimum functionality needed to remove friction?”

- This mindset ensures you're not designing for aesthetic reasons alone, but solving real pain points.

---

### 2. Use a PRD (Product Requirements Document)

- A **PRD helps translate user problems into design goals.**
- Components of a simple PRD:
  - Objective: What feature or flow is being created?
  - User Persona: Who is the primary user?
  - Problem Statement: What is the friction?
  - Success Criteria: How do we know the solution works?

---

### 3. Ideation & Brainstorming

- Sketch ideas *before* building screens. Multiple rough drafts > single polished idea.
- Use tools like:
  - Crazy 8s: 8 ideas in 8 minutes
  - Mind maps: Cluster features around core user goal
- Encourage diversity of thought: no “bad” ideas in early ideation.

---

### 4. Map the User Flow

- Think in terms of **states and transitions**: What happens when a user clicks, swipes, confirms?
- Common flow structure:
  1. Entry Point (user arrives on screen)
  2. Action (e.g., selects, fills out, clicks)
  3. Feedback/Confirmation
  4. Next Step or Exit

- Focus on **clarity** and **logical progression** over visual fidelity.

---

### 5. Ask ChatGPT to Assist with Scenario Framing

- The course suggested using AI tools to flesh out the fictional context:
  - “Can you describe a user who is trying to use this feature?”
  - “What pain points might they experience here?”
  - “What flow might be intuitive for this kind of user?”

This encourages **empathetic reasoning** and helps avoid defaulting to your own preferences.

---
```
[Home Screen]
     |
     v
[Personalized Recommendations]
     |
     |---> [Info Icon] → [Why This Was Recommended]
     |
     |---> [Filter Button] → [Adjust Preferences]
     |
     v
[Movie Detail Page]
     |
     |---> [Play Trailer] / [Add to Watchlist]
     |
     v
[Feedback Prompt]
  ("Did you like this rec?") → [👍 / 👎] → (Improves future results)
```
---

## Simple Prototype & Use Flow - AI Recommender System

### 1. User Flow Diagram

```
[Home Screen]
     |
     v
[Personalized Recommendations]
     |
     |---> [Info Icon] → [Why This Was Recommended]
     |
     |---> [Filter Button] → [Adjust Preferences]
     |
     v
[Movie Detail Page]
     |
     |---> [Play Trailer] / [Add to Watchlist]
     |
     v
[Feedback Prompt]
  ("Did you like this rec?") → [👍 / 👎] → (Improves future results)
```

---

### 2. User Pain Points & Design Responses

| **User Pain Point** | **Design Response** |
|---------------------|----------------------|
| "I don’t know *why* I'm being shown this." | **Info icon** surfaces an explanation like: “Because you rated Arrival 5 stars” |
| "I feel like I can’t influence what I see." | **Filter controls** let users adjust genre, mood, recency, language |
| "The recs are always the same — not enough variety." | Add a **'Surprise Me'** or **serendipity toggle** in filter panel to diversify |
| "I don’t trust how my data is used." | Display **data use summary** under recommendations with option to adjust personalization |
| "I want to give feedback to improve results." | **Thumbs up/down** on each rec actively shapes future outputs |
| "I’m overwhelmed or disengaged by the UI." | Streamline layout with clear primary actions: Watch Trailer, Add to Watchlist, Skip |

---

### 3. Design Intent Summary

This user flow reflects core human-centered design principles:
- **Transparency**: Showing why a recommendation appears
- **Control**: Giving the user input into the system logic
- **Feedback**: Reinforcing that their actions (likes/dislikes) matter
- **Empathy**: Acknowledging the user’s desire for variety, trust, and low-friction decision making

By anticipating these pain points, the design doesn't just "recommend" — it *invites collaboration* with the user.

---

### 4. Optional Visual Sketch

Can build it using [Excalidraw](https://excalidraw.com) for a quick, clean wireframe.