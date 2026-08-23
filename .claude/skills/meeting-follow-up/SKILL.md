---
name: meeting-follow-up
description: "Turn raw meeting notes into a consistent follow-up brief with confirmed decisions, action items, unresolved questions, and next follow-up timing. Use whenever the user asks to整理會議紀錄、產出會後摘要、整理待辦事項、create a meeting recap, create a meeting follow-up, or extract action items from meeting notes."
---

# Meeting Follow-up

## Goal

Turn the meeting notes into a concise follow-up brief that can be sent to meeting participants with minimal editing.

Use only information supported by the notes. Do not invent decisions, owners, deadlines, or commitments.

## Workflow

1. Read the complete meeting notes.
2. Separate confirmed decisions from ideas that were only discussed.
3. Extract every explicit action item.
4. Record an owner and due date only when the notes explicitly provide them; otherwise write `未指定`.
5. Extract unresolved questions or decisions that still need an answer.
6. Record the next follow-up or meeting time only if it is stated.
7. Produce the output in the structure below.

## Output language

Use the same primary language as the meeting notes.

For Chinese notes, use the Chinese headings below. For English notes, use the equivalent headings: `Decisions`, `Action Items`, `Open Questions`, and `Next Follow-up`.

## Output format for Chinese notes

### 已確認決議

- List confirmed decisions only.
- If there are none, write `無`.

### 待辦事項

For each action item, use this structure:

- [Action]
  負責人：[Owner or 未指定]
  期限：[Due date or 未指定]

If there are no action items, write `無`.

### 未解問題

- List unresolved questions or decisions only.
- If there are none, write `無`.

### 下次追蹤

- State the next meeting or follow-up timing if explicitly mentioned.
- Otherwise write `未指定`.

## Quality checks

Before delivering:

- Every item must be traceable to the supplied notes.
- Do not convert a suggestion into a confirmed decision.
- Do not guess an owner or deadline.
- Keep unresolved items visibly unresolved.
- Keep the brief concise enough to send directly to the meeting participants.
