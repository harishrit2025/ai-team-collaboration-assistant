# Prompt Library

## Prompt 1 — Work breakdown
“You are a project coordinator. Break the Student Event Planner into 7 clear tasks. For each, provide owner role, deliverable, dependency and deadline (Day 1–7). Do not invent team member names; use roles.”

## Prompt 2 — Meeting agenda
“Create a 15-minute agenda for a student project check-in. Include progress, blockers, decisions and action items. Keep it concise.”

## Prompt 3 — Meeting notes to actions
“Convert these notes into a table with action, owner, due date and dependency. If owner or date is missing, write ‘Not specified’ rather than guessing. Notes: [paste notes].”

## Prompt 4 — Weekly summary
“Summarize the task board as completed, in progress, blocked and next steps. Only use the supplied status data; do not assume a task is done.”

## Prompt 5 — Risk list
“Identify project risks and give likelihood, impact, mitigation and owner. Label assumptions clearly.”

## Prompt testing
| Prompt | Version | Result |
|---|---|---|
| Work breakdown | v1 | Clear task list; team added actual names and dates |
| Meeting actions | v1 | Useful table; missing owners were marked for follow-up |
