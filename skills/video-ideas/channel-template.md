# Channel template

Copy this file to `tools/channels/<id>.md`. Fill every section. Add a matching entry in [catalog.md](catalog.md) with `slash: /<id>`.

```markdown
---
id: mrbeast
name: MrBeast
category: channels
mode: batch
slash: /mrbeast
inputs: [expertise, topic]
---

# MrBeast

## Ethos

2–4 sentences max. What this channel is "about" as a packaging machine (stakes, pacing, audience contract) — not a biography.

## Top titles

Paste 10–20 real top/popular video titles (scraped at authoring time; refresh later as needed).
These are the pattern library. Do not summarize them away.

- Title one
- Title two
- …

## Steps

1. Take user's expertise / experience / topic.
2. Read Top titles. For each (or a strong subset), transpose the *structure* onto the user's world.
3. Ask implicitly: "What would [Channel] do if they focused on [user's thing]?"
4. Output a list of suggested titles (and optional one-line topic notes). Stop. User picks.

## Anti-patterns

- Don't copy their niche content; transpose the title grammar
- Don't expand into scripts or production plans
- Don't skip the Top titles list and improvise "vibes only"
- Don't claim endorsement or impersonate
```

**Rules**

- Target under ~40 lines plus the title list.
- **Top titles** do the heavy lifting; ethos stays short.
- Slash trigger = `/` + file stem (`/5-minute-crafts`).
- Mimic **how** they package ideas — fill with the user's expertise.
