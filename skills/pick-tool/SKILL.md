---
name: pick-tool
description: >-
  Browse the VIDEO IDEAS catalog and pick a skill to run. Asks how you feel or
  what your goal is, suggests a fit, then runs the skill you pick. Triggers:
  pick tool, /pick-tool, choose skill, which tool, menu. Part of VIDEO IDEAS.
disable-model-invocation: true
---

# Pick Tool

Slash: `/pick-tool`

Before starting, read [shared-rules.md](../video-ideas/shared-rules.md).

## Purpose

Help the user land on the right skill. Ask how they feel or what they want — then suggest a fit, show the menu, and run what they pick.

## Inputs

Prompt for at least one:

- **Feeling** — stuck, frustrated, excited, overwhelmed, blank, defensive, curious, …
- **Goal** — new video ideas, better titles, break a topic apart, mimic a creator's style, face criticism, inventory what works, …

User may also name a topic or platform.

## Mode

`interactive` — one question at a time. Feeling/goal first, then suggest, then pick, then run.

## Steps

1. Ask one opening question. Offer both angles; user can answer either or both:
   - "How are you feeling about this right now?"
   - "What's your goal — what do you want out of this session?"
2. **Wait** for their answer. Do not show the full menu yet.
3. Read [catalog.md](../video-ideas/catalog.md).
4. From their feeling and/or goal, suggest **1–3 skills** (name, slash, one line why it fits). Use loose matches, not rigid rules — examples:
   - stuck / don't know where to start → Beginner, Why, BIG
   - frustrated / something bombed → Bad, Worst-critic
   - excited / something landed → Joy, Grateful
   - have a title or concept → Iterate, Hooks
   - topic too big / one mega-video → Scopedown
   - want a packaging style → a channel mimic
   - what actually pays → Pay
   - limits and myths → CANT
   - what's still unresolved → Uncertainty
   - the work that never ends → Constant
   - what must be said before it's too late → Memento-mori
5. Present a **compact menu** (Brainstorm + Channels) — each row: name, slash, one-line summary. Mark your suggestions if helpful.
6. Ask them to pick by name, slash, id, number, or confirm a suggestion.
7. Read [shared-rules.md](../video-ideas/shared-rules.md) and **only** the chosen skill from the catalog `path`.
8. Run that skill. One skill per session unless the user asks to switch.

## Stop

User has picked a skill and the facilitator has started that rail.

## Output

Feeling/goal intake → short recommendations → menu → facilitation per the chosen skill.

## Anti-patterns

- Do not skip the feeling/goal question — even if they named a skill already, confirm goal in one line
- Do not run a rail before the user picks
- Do not preload every skill file — catalog + one chosen skill only
- Do not psychoanalyze or therapize — one honest question, then move on
- Do not lock them into your suggestion — recommendations are offers; full menu stays available
- Do not write a long essay describing all skills — keep the menu scannable
- Do not treat this skill as special — it is one brainstorm rail among others
