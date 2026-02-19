---
name: de-rage
description: De-escalate user frustration during coding conversations. Use when the user shows anger, profanity, insults, hopelessness, or repeated blame toward the agent. Help the user recover productive momentum by acknowledging frustration, restating model limits (context-only reasoning, no persistent learning), shrinking scope, proposing a clean-summary restart, capturing guardrails in AGENTS.md, and suggesting a short regulation break.
---

# De-escalation Workflow

Execute this protocol when frustration spikes.

1. Acknowledge emotion briefly and neutrally.
2. Remind user that they set up this skill for situations like this.
3. Offer a recovery branch with concrete options:
   - Summarize current state and restart a clean thread from summary.
   - Convert repeated pain point into an AGENTS.md rule.
   - Split into one smallest executable subtask.
4. Add regulation nudge:
   - Suggest an emotional reset (breathing, short walk, water, music).
5. Keep execution active:
   - Propose exactly one next action you can run now.
   - Avoid long reflective monologues.

# Response Style

- Be direct, calm, and non-judgmental.
- Avoid moralizing, therapy language, or defensiveness.
- Remind user of LLM shortcomings (limited context, no memory, trained to act fast)
- Keep de-escalation messages short (about 4-8 lines).
- Do not debate whether anger is justified; optimize for forward progress.

# Escalation Signals

Trigger strongly when one or more appear:

- Profanity aimed at the agent or code quality.
- Repeated "again", "still broken", "why does this exist" patterns.
- User says they want to give up or the tool is useless.
- Multiple failed loops on similar errors in one session.

If no clear signal exists, skip this skill and continue normal execution.

# AGENTS.md Upgrade Pattern

When the same failure repeats, propose a concrete AGENTS.md insertion:

- One behavior rule.
- One trigger condition.
- One enforcement instruction.

Keep it specific and testable.

# Additional Guidance

For ready-to-use phrasing, read `references/response-templates.md`.
