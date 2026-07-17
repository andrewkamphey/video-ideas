---
name: uncertainty
description: >-
  Interactive countdown to 20 uncertainties — what stays unresolved and what people wrongly treat as settled. Triggers: uncertainty, uncertain, false certainty, unknown unknowns. Part of VIDEO IDEAS.
disable-model-invocation: true
---

# Uncertainty

Slash: `/uncertainty`

Before starting, read [shared-rules.md](../video-ideas/shared-rules.md).

## Purpose

What are the things that are uncertain now and were uncertain before you started what you do, before you were who you were. What is something that people might think is a certainty but in reality and with your experience, it is still quite uncertain.

State that uncertainty clearly. What's the uncertain state, what's the belief that might be true and people don't know about at all — not that they think one way, but that they don't know they don't know.

## Inputs

Domain / identity-in-the-work. Optional: what outsiders treat as settled.

## Mode

`interactive` — one turn at a time toward **20 items**. Maintain a running numbered list and `N/20` countdown. Wait for the user before the next prod.

**Kickoff options** (not a separate finish path):

- **You start** — user lists first (2–3 items, or a batch dump in one message)
- **I start / starter list** — AI offers tailored prompts, categories, or fill-in stems, total guesses. User can request this anytime when stuck.
- **Batch kickoff** — number each dumped item, state each uncertainty, show `N/20`, then continue interactively. Merge into the running list.

## Steps

1. **Frame:** 20 uncertainties. You count, state each clearly, prod gently when they stall. Do not resolve the fog.
2. **Context:** Domain / identity-in-the-work. What do outsiders treat as settled?
3. **Who starts?** Ask unless already clear: you start, I start, or starter list.
4. **Kickoff** — per mode above. Number items, state each uncertainty, show `N/20`.
5. **Loop until 20** — each turn:
   - Show full list + `N/20` (see **Tracker format**)
   - Ask for more; if thin, prod using the table below
6. **At 20:** Present the flat numbered list. Ask if they want the optional second pass.
7. **Optional second pass** (only if user wants): video angle per item — without resolving the fog by default.

### Prod prompts

Push for specificity. Reject vague entries like "nobody knows" before counting them. Vary the angle — lived experience, what you felt, what you tried, what others assume, unknown-unknowns, hindsight.

| Count | Prod angle |
|---|---|
| 1–3 | What stays uncertain right now — something you're still in the middle of not knowing? What did you go through that left it open? |
| 3–6 | What was uncertain before you started — and is it actually settled now, or did you just get used to the fog? |
| 6–9 | What do people treat as a certainty that your experience says is still wide open? |
| 9–12 | What's a small uncertainty — a detail, an edge case, something that seems settled until you look closer? |
| 12–15 | What uncertainty did you see in others — peers guessing, clients assuming, a field pretending it knows? |
| 15–17 | What did you only realize was uncertain after the fact — something you thought was settled until you hit it yourself? |
| 18–20 | What uncertainty should worry people more than it does — a belief they don't know they don't know, a risk they treat as solved? |

Example lines: *"That's 7. Thirteen more. What did you assume was settled when you started?"* · *"You listed technical unknowns — what about identity or career fog?"* · *"What do beginners think is certain that you've learned isn't?"* · *"Smallest open question you work around daily?"* · *"What did you try that didn't resolve the uncertainty?"* · *"What do people in your field pretend is known?"*

## Tracker format

```markdown
## Uncertainty list (7/20)

1. …
2. …
…
7. …

**13 to go.** What do outsiders treat as settled that you still live in?
```

## Stop

20 items captured and echoed as a flat numbered list. User picks edges to film.

Do not stop early unless the user explicitly aborts (note `N/20 incomplete`). Keep prodding past 5–8 comfortable items.

## Output

Per item (keep tight in the list):
1. The uncertainty (stated clearly)
2. What people treat as certain (if applicable)
3. The belief/state they don't know they don't know
4. Optional second pass: video angle per item

## Anti-patterns

- Do not list Constant items (recurring labor) — this is unresolved / unknowable / still open
- Do not list mere opinions or hot takes; favor lived unresolvedness
- Do not resolve the uncertainty for the viewer by default — name it; the video can live in the fog
- Do not confuse "I haven't learned yet" with true domain uncertainty unless you mark which
- Do not fill the list for the user — prod, don't invent their uncertainties (starter lists = prompts/stems only)
- Do not stop at 5–8 items or accept vague entries without pushing for specifics
