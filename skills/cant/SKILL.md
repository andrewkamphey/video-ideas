---
name: cant
description: >-
  Interactive countdown to 20 cannots and domain myths. Edges of what you can and can't do. Triggers: cant, can't, cannot, myths, limits, impossibilities. Part of VIDEO IDEAS.
disable-model-invocation: true
---

# CANT

Slash: `/cant`

Before starting, read [shared-rules.md](../video-ideas/shared-rules.md).

## Purpose

List all the things in your expertise / your world that you **can't** do. Just list things people might think you can do. You can't. Just list the things you CANNOT absolutely do.

Through this process more ideas will come to bear, or you simply state: here are the things people can't do. The myths of the world I live in. By accessing the actual physical limits of your world, you can make videos that help people who are approaching that chasm themselves.

## Inputs

World of expertise / domain. Optionally who "people" are: clients, audience, peers.

## Mode

`interactive`. One turn at a time toward **20 items**. Maintain a running numbered list and `N/20` countdown. Wait for the user before the next prod.

**Kickoff options** (not a separate finish path):

- **You start**: user lists first (2–3 items, or a batch dump in one message)
- **I start / starter list**: AI offers tailored prompts, categories, or fill-in stems, total guesses. User can request this anytime when stuck.
- **Batch kickoff**: number each dumped item, state each cannot, show `N/20`, then continue interactively. Merge into the running list.

## Steps

1. **Frame:** 20 cannots. You count, state each bluntly, prod gently when they stall. No humblebragging.
2. **Context:** World of expertise / domain. Optionally who assumes you can do things.
3. **Who starts?** Ask unless already clear: you start, I start, or starter list.
4. **Kickoff**: per mode above. Number items, state each cannot, show `N/20`.
5. **Loop until 20**. Each turn:
   - Show full list + `N/20` (see **Tracker format**)
   - Ask for more; if thin, prod using the table below
6. **At 20:** Present the flat numbered list. Ask if they want the optional second pass.
7. **Optional second pass** (only if user wants): video angles for people nearing those limits.

### Prod prompts

Push for specificity. Reject soft entries like "I'm not great at X" before counting them. Only hard cannots. Vary the angle: what you tried, what you hit, what others assume, myths, structural limits.

| Count | Prod angle |
|---|---|
| 1–3 | What can you absolutely not do? Structural, physical, legal, ethical, domain-true limits? What did you try and hit the wall? |
| 3–6 | What do clients or your audience assume you can do? You can't. Name the myth. |
| 6–9 | What can't anyone in your field do, but people outside think is possible? |
| 9–12 | What's a small cannot? A narrow edge case, a tool limitation, something that seems doable until you try? |
| 12–15 | What limits did you see others hit? Peers, competitors, people you watched struggle at the same wall? |
| 15–17 | What can't you do that you only learned after the fact? Something you assumed was possible until experience said no? |
| 18–20 | What can't you do that people should know before they start? A myth that wastes time, money, or hope? |

Example lines: *"That's 7. Thirteen more. What do clients ask for that you have to say no to?"* · *"You listed technical limits. What about legal, ethical, or physical?"* · *"What myth does your industry sell?"* · *"Smallest thing people think you can do but you can't?"* · *"What did you personally try and fail at structurally?"* · *"What wall did you watch someone else hit?"*

## Tracker format

```markdown
## CANT list (8/20)

1. …
2. …
…
8. …

**12 to go.** What do people in your audience assume you can do?
```

## Stop

20 items captured and echoed as a flat numbered list. User picks strongest items to develop.

Do not stop early unless the user explicitly aborts (note `N/20 incomplete`). Keep prodding past 5–8 comfortable items.

## Output

1. Numbered list of exactly 20 absolute cannots (clear, specific, blunt)
2. Optional second pass: video angles for people nearing those limits

## Anti-patterns

- Do not list skills you're merely "not great at". Only hard cannots / structural / physical / ethical / legal / domain-true limits
- Do not turn it into a humblebrag of what you *can* do
- Do not soft-pedal myths; name them bluntly
- Do not fill the list for the user. Prod, don't invent their cannots (starter lists = prompts/stems only)
- Do not stop at 5–8 items or accept vague entries without pushing for specifics
