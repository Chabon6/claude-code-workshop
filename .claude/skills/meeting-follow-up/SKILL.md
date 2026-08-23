---
name: meeting-follow-up
description: Turn raw meeting notes into a consistent follow-up brief with decisions, action items, open questions, and follow-up timing. Use whenever the user asks to整理、總結、產出會後紀錄、meeting recap、meeting follow-up, or extract action items from meeting notes.
---

# Meeting Follow-up

## Goal

Turn the meeting notes supplied by the user into a concise, send-ready follow-up brief.

Use only information supported by the notes. Do not invent decisions, owners, deadlines, or commitments.

## Workflow

1. Read the complete meeting notes.
2. Separate confirmed decisions from ideas that were only discussed.
3. Extract every explicit action item.
4. Record an owner and due date only when the notes explicitly provide them; otherwise write `未指定`.
5. Extract unresolved questions that still need an answer.
6. Record the next follow-up or meeting time only if it is stated.
7. Produce the output in the required structure below.

## Output format

### Decisions
- List confirmed decisions only.
- If there are none, write `無`.

### Action Items

| Action | Owner | Due |
|---|---|---|
| ... | ... | ... |

If there are no action items, write `無` instead of an empty table.

### Open Questions
- List unresolved questions only.
- If there are none, write `無`.

### Next Follow-up
- State the next meeting or follow-up timing if explicitly mentioned.
- Otherwise write `未指定`.

## Quality checks

Before delivering:

- Every item must be traceable to the supplied notes.
- Do not convert a suggestion into a confirmed decision.
- Do not guess an owner or deadline.
- Keep the brief concise enough to send directly to the meeting participants.
