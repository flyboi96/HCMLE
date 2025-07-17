# Day 3: Design Critique – macOS System Settings App

## 1. Overview
- **Product**: macOS System Settings App
- **Platform**: macOS Sequoia
- **Focus Area**: Wi-Fi settings interface
- **Goal**: Identify usability issues and propose improvements using UX principles.

---

## 2. Quick Description
The Wi-Fi section in System Settings allows users to manage wireless connections. It includes options to view available networks, configure details, and manage known networks. While functionally complete, its layout and interaction design introduce usability challenges. In the words of Don Norman, *“when a design is not intuitive, the user blames themselves.”* The design should instead make correct actions obvious.

---

## 3. Usability Issues

| Issue | Location | Why it Matters | UX Principle Violated |
|-------|----------|----------------|------------------------|
| Important actions (like 'Join Other Network') are hidden behind a "More…" menu | Bottom of Wi-Fi section | Adds unnecessary steps for power users | Visibility, Efficiency of Use |
| Network list is scrollable in a small panel with no sorting or prioritization | Main Wi-Fi list | Makes it harder to find your intended network | Information Architecture |
| Wi-Fi settings icon blends in and lacks clear feedback when clicked | Top of panel | Confuses new users who expect a more explicit call to action | Feedback, Affordance |
| "Details…" label is vague and action-ambiguous | Connected network row | Leaves the user unsure of what clicking will do | Discoverability, Mappings |
| Minimal visual hierarchy between known, unknown, and personal hotspot networks | Entire Wi-Fi list | Users can't quickly distinguish trusted from unknown networks | Recognition over Recall |

---

## 4. Suggested Improvements
- **Expose key actions** such as "Join Other Network" and "Advanced Settings" with labeled buttons instead of hiding them behind vague options like “Other…”
- **Redesign the network list** to prioritize known or secure connections, and allow for user-defined favorites or sorting
- **Clarify labels** like “Details…” to specify the action, e.g., “Network Settings”
- **Enhance feedback and consistency** with visual cues (hover states, color changes, icon animations) so users understand what can be clicked
- **Apply hierarchy** through spacing, contrast, or group labels (e.g., “Trusted Networks,” “Public,” “Hotspots”)

---

## 5. Summary
The macOS System Settings app's Wi-Fi interface reflects a modern aesthetic, but sacrifices clarity and usability in the process. It prioritizes minimalism over effective communication, hiding common actions and flattening visual hierarchy. As Don Norman might say, *“Good design is actually a lot harder to notice than poor design, in part because good design fits our needs so well that the design is invisible.”* Unfortunately, the design here draws attention not because it works, but because it gets in the way.

By focusing on clear labels, surfacing frequent actions, and applying structure to the interface, Apple could transform this screen into something not just beautiful — but truly usable.