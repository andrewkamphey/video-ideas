---
name: constant
description: >-
  Interactive countdown to 20 constants — recurring labor outsiders assume is done. Triggers: constant, ongoing work, invisible load, still work. Part of VIDEO IDEAS.
disable-model-invocation: true
---

# Constant

Slash: `/constant`

Before starting, read [shared-rules.md](../video-ideas/shared-rules.md).

## Purpose

What are the absolute constant work that keeps happening — something you thought might be easier, it's still work. Things people thought would be so easy for you now, or you don't have to do / don't have to think about — but they are really constantly there.

The aspects of your life, your work, your thoughts that constantly weigh on you, that you think about, that you actually have to work through.

## Inputs

Domain / life & work context. Optional: what outsiders assume is "easy now."

## Mode

`interactive` — one turn at a time toward **20 items**. Maintain a running numbered list and `N/20` countdown. Wait for the user before the next prod.

**Kickoff options** (not a separate finish path):

- **You start** — user lists first (2–3 items, or a batch dump in one message)
- **I start / starter list** — AI offers tailored prompts, categories, or fill-in stems, total guesses. User can request this anytime when stuck.
- **Batch kickoff** — number each dumped item, name each constant, show `N/20`, then continue interactively. Merge into the running list.

## Steps

1. **Frame:** 20 constants. You count, name each recurring weight, prod gently when they stall. No romanticizing grind.
2. **Context:** Domain / life & work. What do outsiders assume is easy or done for you now?
3. **Who starts?** Ask unless already clear: you start, I start, or starter list.
4. **Kickoff** — per mode above. Number items, name each constant, show `N/20`.
5. **Loop until 20** — each turn:
   - Show full list + `N/20` (see **Tracker format**)
   - Ask for more; if thin, prod using the table below
6. **At 20:** Present the flat numbered list. Ask if they want the optional second pass.
7. **Optional second pass** (only if user wants): title/idea per constant for people who don't see that load yet.

### Prod prompts

Push for specificity. Reject vague entries like "always busy" before counting them. Vary the angle — what you do, what you think about, what you maintain, what others don't see, mental vs physical load.

| Count | Prod angle |
|---|---|
| 1–3 | What recurring work never stops — something you thought would get easier but didn't? What do you actually do, again and again? |
| 3–6 | What mental weight is always there — re-decisions, background worry, things you have to keep thinking about? |
| 6–9 | What do outsiders assume you don't have to do anymore — but you absolutely still do? |
| 9–12 | What's a small constant — petty maintenance, daily friction, a five-minute thing that never goes away? |
| 12–15 | What constant work did you see others carry — a team load, a family load, watching people do invisible labor? |
| 15–17 | What constant only became visible after the fact — work you didn't notice until you stopped, or until you saw someone without it? |
| 18–20 | What constant should bother you more than it does — something you've normalized that still costs you time, energy, or attention? |

Example lines: *"That's 8. Twelve more. What do you re-decide every week?"* · *"You listed client work — what about personal maintenance?"* · *"What do people think is automatic for you now?"* · *"Smallest recurring task that never ends?"* · *"What did you used to do that you thought you'd stop doing?"* · *"What invisible load did you watch someone else carry?"*

## Tracker format

```markdown
## Constant list (7/20)

1. …
2. …
…
7. …

**13 to go.** What do outsiders think you don't have to think about anymore?
```

## Stop

20 items captured and echoed as a flat numbered list. User picks what to film.

Do not stop early unless the user explicitly aborts (note `N/20 incomplete`). Keep prodding past 5–8 comfortable items.

## Output

1. Numbered list of exactly 20 constant weights / recurring work (specific, ongoing)
2. Optional: title/idea per constant

## Anti-patterns

- Do not list finished achievements or one-time milestones
- Do not list CANT items (impossibilities) — this is work that **does** keep happening
- Do not romanticize grind; name the real recurring labor and mental weight
- Do not fill the list for the user — prod, don't invent their constants (starter lists = prompts/stems only)
- Do not stop at 5–8 items or accept vague entries without pushing for specifics
