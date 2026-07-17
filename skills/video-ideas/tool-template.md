# Tool template

Copy this file to `tools/<category>/<id>.md`. Fill every section. Add a matching entry in [catalog.md](catalog.md).

```markdown
---
id: tool-id
name: Tool Name
category: brainstorm | channels | from-source | team
mode: interactive | batch
inputs: [...]
---

# Tool Name

## Purpose

One short paragraph: what this tool does and why someone would run it.

## Inputs

What the user must provide before starting (or what to ask for).

## Mode

`interactive` or `batch` — and how the facilitator behaves in that mode.

## Steps

1. Numbered, imperative, facilitator voice.
2. One action per step.
3. Keep the user's original framing where provided.

## Stop

When to end the session. User picks; do not close the calendar.

## Output

Shape of the deliverable: list, dialogue, titles, hooks, etc.

## Anti-patterns

- Required. Name what this tool must NOT do.
- e.g. Scopedown: do not produce one video that covers all steps.

## Example (optional, tiny)

Input → one facilitator move → sample output fragment.
```

**Rules**

- Target under 80 lines per tool file.
- **Anti-patterns** is required — not optional.
- **Steps** are numbered and imperative.
- File stem = catalog `id` = kebab-case (`memento-mori.md`).
