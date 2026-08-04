# Validation Report — Smart Onboarding

## Testing Overview
Four external participants tested the HiveMind Smart Onboarding Figma
prototype, using all four tasks defined in `testing/tasks.md` and the
script in `testing/test-script.md`. None of the participants were members
of the project group. Full individual notes are available in
`testing/participant-notes/`.

| Participant | Role |
|---|---|
| T01 | Marketing |
| T02 | Frontend Designer |
| T03 | Office Worker |
| T04 | Receptionist |

## Task Results

| Task | Hypothesis | Result |
|---|---|---|
| Task 1 — Find the correct document via the AI assistant | H2 | 4/4 succeeded within the expected time |
| Task 2 — Find the correct contact via the support suggestion feature | H3 | 4/4 succeeded, ~45 seconds each (target: 30 seconds) |
| Task 3 — Complete Day 1 tasks and understand what's next | H1 | 4/4 succeeded within the expected time |
| Task 4 — Recognise role-specific content | H4 | 4/4 succeeded within the expected time |

All four participants successfully completed all four usability tasks.
Task 2 consistently took longer than the target across every participant,
while the remaining tasks were completed within the expected time.

## Hypotheses — Validation Status

| Hypothesis | Status | Basis |
|---|---|---|
| H1 — Guided first steps with visible progress | Supported | All participants completed Day 1 tasks and understood next steps without difficulty |
| H2 — Centralised information / single source of truth | Supported | All participants located the correct document via the AI assistant easily |
| H3 — Trustworthy, contextual support | Partially supported | All participants succeeded, but the consistent ~45-second average against a 30-second target suggests room to streamline the flow |
| H4 — Role-specific content over generic training | Supported | All participants correctly recognised and described the role-tailored content |

The consistent task completion across participants from different
professional backgrounds (marketing, design, office administration,
reception) suggests that the main prototype flow was understandable and
usable to a general working audience, not just to people already familiar
with the project.

## Qualitative Feedback
All four participants gave generally positive feedback about the
prototype — describing it as easy to follow, well designed, and simple
to complete tasks in. No participant reported specific difficulties.

## Limitations of This Round
The feedback was broadly positive but did not capture detailed comments
about individual screens, specific usability problems, or meaningful
differences between participants. This consistency is a genuine
limitation of the testing process itself — a more rigorous round would
be expected to surface at least some individual variation or friction
points, even where the overall outcome is successful. As such, this
round provides useful initial evidence of usability but should not be
treated as comprehensive validation.

## Recommendations
1. **Streamline the support suggestion flow.** Every participant took
   longer than the 30-second target on Task 2 — investigate whether
   simplifying the question-type selection step reduces this.
2. **Run a more detailed follow-up testing round**, using screen-specific
   questions and think-aloud observation, to capture individual variation
   and smaller usability issues that a general pass/fail summary cannot.
3. **Validate the expanded prototype.** The prototype has since grown
   from 6 to 16 screens, adding confirmation states (Task Completed,
   Request Submitted, Notification popup) introduced in response to the
   heuristic review. These additions were not covered by the testing
   above — a short follow-up check, even informal, would let the group
   confidently claim these screens are validated too.

## Overall Conclusion
Based on this round of testing, the prototype supports all four of the
group's hypotheses — H1, H2, and H4 fully, and H3 partially, pending a
faster support suggestion flow. All four tasks were completed
successfully by all four participants, providing solid initial evidence
that the core Smart Onboarding concept is usable across a general working
audience. The main actionable finding is the Task 2 timing gap, and the
main process improvement for future testing is capturing more detailed,
participant- and screen-specific feedback.
