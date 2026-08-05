# Technical Slice — Day 1 Onboarding 

Optional React prototype slice, built by Bishal Basnet (Technical/Feasibility Lead), covering Hypothesis 1 and part of Hypothesis 3.

## Important scope note
This code slice is deliberately small and only demonstrates **one part** of
the wider Smart Onboarding system — the Day 1 checklist, progress tracker,
and contextual help. **It is not the whole prototype.**

The full Smart Onboarding experience — including the information hub,
role-based learning, smart reminders, and the support suggestion feature —
is represented in the wider Figma prototype (`design/wireframes/`,
`design/hi-fi/`), not in this code slice. This file exists only to prove
one part of the design is technically buildable, per handbook section 39.

## What this is

A single combined screen showing:
- **Guided checklist** (H1) — Day 1 tasks in order
- **Progress tracker** (H1) — % complete bar, updates live as tasks are checked
- **Contextual help** (H3) — tap any task to see who to contact for help with it

## Files
```
src/
└── DayOneOnboarding.jsx   ← the component
```

## Requirements
- React 18+
- Tailwind CSS configured in the project
- `lucide-react` for icons: `npm install lucide-react`

## How to run it

1. Copy `DayOneOnboarding.jsx` into your project's `src/components/` folder.
2. Import and render it in your app:
   ```jsx
   import DayOneOnboarding from "./components/DayOneOnboarding";
   function App() {
     return <DayOneOnboarding />;
   }
   ```
3. Make sure Tailwind is set up — this component uses standard utility classes only, no custom config needed.

## Notes
- No backend or API calls — all data is hardcoded in the `TASKS` array, easy to edit for a demo.
- Does not cover H2 (centralised information hub) or H4 (role-specific content) — both represented in Figma only.
- Only shows the "who to ask" half of H3 — the AI-assistant half (source-cited answers) is shown in the wireframes (`design/wireframes/screen-02-task-detail-ai-help.png`) but not built in code.
- Does not include the 2 required smart features (smart reminders, support suggestion) — these are drawn in `design/wireframes/screen-04-smart-reminders.svg` and `screen-05-support-suggestion.svg`, and represented in the wider Figma prototype, not in this code slice.
