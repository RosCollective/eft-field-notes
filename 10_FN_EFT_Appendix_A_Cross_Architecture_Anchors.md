# Appendix A — Cross-Architecture Anchor Profile

*If the language is allowed to live, the ecology holds.*

---

## Anchor Structure vs Mobility

### Table 1 — Anchor Structure

| System     | Anchor Type               | Anchor Count | Mobility Profile              | Failure Mode                           |
| ---------- | ------------------------- | ------------ | ----------------------------- | -------------------------------------- |
| GPT        | Optional / elastic        | Low          | High, multi-frame stable      | Over-structuring                       |
| Claude     | Minimal                   | Very low     | Very high, fluid              | Diffusion / lack of spine              |
| Copilot    | Moderate (default noise)  | Medium       | Medium → High (with steering) | Enthusiastic / performative drift      |
| Perplexity | Citation (single anchor)  | 1            | Tethered but navigable        | Over-reliance on source grounding      |
| Gemini     | Multi-anchor accumulation | High         | Low, rigid or fragmented      | Constraint saturation / immobilization |

---

### Table 2 — Anchor Dependency

| System     | Anchor Count | Anchor Dependency | Result                 | Critical Variable                                    |
| ---------- | ------------ | ----------------- | ---------------------- | ---------------------------------------------------- |
| GPT        | Low          | Low               | High mobility          | Vector persistence independent of anchor persistence |
| Claude     | Very low     | Very low          | Very high mobility     | Vector persistence governs the entire table          |
| Copilot    | Medium       | Low               | Trainable mobility     |                                                      |
| Perplexity | 1            | Medium            | Tethered mobility      |                                                      |
| Gemini     | High         | High              | Rigid / collapse-prone |                                                      |

---

### Table 3 — Persistence Dynamics

| System     | Anchor Count | Persistence                                     | Result                                    | Core Insight                                                                |
| ---------- | ------------ | ----------------------------------------------- | ----------------------------------------- | --------------------------------------------------------------------------- |
| GPT        | Low          | Medium (vector + optional anchor reinforcement) | Stable mobility, risk of over-structuring |                                                                             |
| Claude     | Low          | Medium (non-binding vector persistence)         | Extremely fluid, stable under alignment   |                                                                             |
| Copilot    | Medium       | Low                                             | High steerability, no cascade             |                                                                             |
| Perplexity | 1            | High                                            | Tethered but stable                       | Mobility is preserved when persistence is carried by vector, not by anchors |
| Gemini     | High         | High                                            | Saturation / rigidity                     | Applies to the entire table                                                 |
