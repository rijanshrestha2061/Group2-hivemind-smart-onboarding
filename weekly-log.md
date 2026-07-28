# Weekly Log

## Week 1

### Completed
- Reviewed all 6 group interview transcripts (P01, P02, P03, P05, P06, P04) for technical feasibility — Technical/Feasibility Lead — 19 July 2026 — 1.5 hours
- Synthesised recurring pain-point themes across all transcripts, saved to `research/synthesis/research-synthesis.md` — Technical/Feasibility Lead — 19 July 2026 — 1 hour
- Wrote group hypotheses grounded in interview evidence, saved to `docs/hypotheses.md` — Technical/Feasibility Lead — 19 July 2026 — 45 minutes
- Drafted success metrics tied to each hypothesis, saved to `docs/success-metrics.md` — Technical/Feasibility Lead — 19 July 2026 — 30 minutes
- Logged feasibility decisions and rationale in `docs/decisions.md` — Technical/Feasibility Lead — 19 July 2026 — 20 minutes
- Built the Week 3 technical slice early (Day 1 onboarding view) in `src/DayOneOnboarding.jsx` — Technical/Feasibility Lead — 19 July 2026
- Wrote `tech/README.md` with setup instructions for the component — Technical/Feasibility Lead — 19 July 2026 — 20 minutes

### Decisions
- Prioritised the guided checklist, progress tracker, and contextual help ideas as low-effort, evidence-backed hypotheses for the Week 3 slice.
- Flagged the centralised onboarding hub and role-specific content ideas as too complex for a code slice — recommended Figma-only or static-mock representation instead.
- Flagged the AI trust/transparency idea as a stretch goal — a UI-only mockup (fake AI answer with source + last-updated date) is feasible without building real AI integration.

### Blockers
- None currently. Waiting on group's Week 2 IA/wireframes before the next feasibility pass.

### Next steps
- Share synthesis and updated hypotheses with the group so everyone works from the same evidence.
- Upload `research-synthesis.md`, `hypotheses.md`, `success-metrics.md`, and `decisions.md` to the group GitHub repo in their correct folders.
- Review Week 2 IA diagram and wireframes for technical feasibility once drafted.

---

## Week 2

### Completed
- Technical/Feasibility Lead — drafted starting-point IA structure for UX/IA Designer (`design/IA/IA-draft.md`), aligned to the 4 hypotheses and journey map — 22 July 2026
- Technical/Feasibility Lead — drafted starting-point low-fidelity wireframes for UI/Prototype Developer (`design/wireframes/wireframes-draft.md`), 4 screens matching the 4 critical tasks — 22 July 2026
- Technical/Feasibility Lead — drafted 4 critical user tasks tied to each hypothesis (`testing/tasks.md`) — 22 July 2026
- Technical/Feasibility Lead — updated `docs/research-plan.md` with completed participant details (6 interviews, P01–P04 excluding P04) — 24 July 2026
- Technical/Feasibility Lead — added placeholder `design/hi-fi/README.md` and project root `README.md`, since both were empty — 24 July 2026
- UX/IA Designer — built and finalised the IA diagram in Figma (5 sections: My Onboarding, Learn & Grow, Information Hub, People & Support, AI Assistant), exported to `design/IA/` — 27 July 2026
- Technical/Feasibility Lead — reviewed UX/IA Designer's IA against the 4 hypotheses for feasibility and traceability — 27 July 2026 — 20 minutes
- _(UI/Prototype Developer — fill in: low-fidelity wireframes finalised in Figma, exported to `design/wireframes/`)_
- _(UX Research & Validation Lead — fill in: reviewed pain-points/hypotheses documents, confirmed accuracy)_
- _(Project Lead — fill in: ran Week 2 self-check before moving to Week 3)_

### Decisions
- Drafts for IA, wireframes, and critical tasks were prepared ahead of schedule to give UX/IA Designer and UI/Prototype Developer a starting point — these are not final and still need to be rebuilt properly in Figma by the actual role owners.
- Reviewed UX/IA Designer's finished IA: confirms to all 4 hypotheses, navigation stays shallow (2 levels, 5 top sections), each hypothesis clearly labelled on the diagram. One deviation from the original draft — H3 (trustworthy contextual support) was split into two separate top-level sections ("People & Support" and "AI Assistant") instead of one combined Help section. Approved as a reasonable restructure since AI Assistant has enough distinct content (source citations, escalation rules, safe-topics guide) to warrant its own space. No feasibility concerns raised.

### Blockers
- UI/Prototype Developer has not yet started building the real Figma wireframes — this is the one remaining Week 2 core deliverable.

### Next steps
- UI/Prototype Developer to build actual Figma wireframes, using the draft as a starting reference
- Once wireframes exist, Technical/Feasibility Lead to review for technical feasibility
- Confirm `testing/tasks.md` tasks are correct before Week 3 begins

---

## Week 3

### Completed
- Day 1 onboarding slice already built ahead of schedule in Week 1 (see above).

### Decisions
- Combined checklist, progress, and help into one cohesive Day 1 view rather than isolated widgets (see `docs/decisions.md`).

### Next steps
- Integrate the component into the group's actual Figma-to-code handoff or demo setup ahead of Week 4.
