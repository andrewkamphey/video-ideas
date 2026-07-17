# Catalog

Full index of VIDEO IDEAS tools. Grouped by category. Load **one** tool file per session.

## TOC

- [Brainstorm](#brainstorm) — 15 tools
- [Channels](#channels) — 12 tools (slash commands)
- [From-source](#from-source) — stub (future tools)
- [Team](#team) — stub (future tools)

---

## Brainstorm

```yaml
id: beginner
name: Beginner
category: brainstorm
mode: interactive
inputs: [concept, topic]
platforms: [any]
triggers: [beginner, beginner questions, socratic, naive questions, beginner list]
path: tools/brainstorm/beginner.md
summary: Pepper beginner questions or dump a naive question list to map the common baseline.
```

```yaml
id: bad
name: Bad
category: brainstorm
mode: batch
inputs: [concept]
platforms: [any]
triggers: [bad, radical acceptance, list the bad, complaints]
path: tools/brainstorm/bad.md
summary: List bad things bluntly — acknowledgment, not obligatory triumph arcs.
```

```yaml
id: joy
name: Joy
category: brainstorm
mode: batch
inputs: [concept]
platforms: [any]
triggers: [joy, joyful, over excited, write and move on]
path: tools/brainstorm/joy.md
summary: Rapid inventory of joy — write it down and move on; don't marinate.
```

```yaml
id: grateful
name: Grateful
category: brainstorm
mode: batch
inputs: [concept]
platforms: [any]
triggers: [grateful, gratitude, who helped, past self]
path: tools/brainstorm/grateful.md
summary: Flow through gratefulness — who, what, why, when; past-self and near-misses.
```

```yaml
id: pay
name: Pay
category: brainstorm
mode: batch
inputs: [concept]
platforms: [any]
triggers: [pay, what people pay for, revenue, transactions, sales not marketing]
path: tools/brainstorm/pay.md
summary: Inventory real money flows — what people actually pay you for, not aspirations.
```

```yaml
id: big
name: BIG
category: brainstorm
mode: batch
inputs: [topic]
platforms: [any]
triggers: [big, big ideas, pillars, searchable, domain map]
path: tools/brainstorm/big.md
summary: Dump 1–2 word searchable pillars for a topic or expertise world — not titles.
```

```yaml
id: cant
name: CANT
category: brainstorm
mode: batch
inputs: [expertise]
platforms: [any]
triggers: [cant, can't, cannot, myths, limits, impossibilities]
path: tools/brainstorm/cant.md
summary: List hard cannots and domain myths — edges of what you can and can't do.
```

```yaml
id: constant
name: Constant
category: brainstorm
mode: batch
inputs: [concept]
platforms: [any]
triggers: [constant, ongoing work, invisible load, still work]
path: tools/brainstorm/constant.md
summary: Name recurring labor outsiders assume is done — the weight that never stops.
```

```yaml
id: uncertainty
name: Uncertainty
category: brainstorm
mode: batch
inputs: [concept]
platforms: [any]
triggers: [uncertainty, uncertain, false certainty, unknown unknowns]
path: tools/brainstorm/uncertainty.md
summary: Surface what stays unresolved and what people wrongly treat as settled.
```

```yaml
id: why
name: Why
category: brainstorm
mode: interactive
inputs: [concept]
platforms: [any]
triggers: [why, why chain, 5 whys, five whys]
path: tools/brainstorm/why.md
summary: Dig five layers of why to sharpen a video idea.
```

```yaml
id: iterate
name: Iterate
category: brainstorm
mode: batch
inputs: [title]
platforms: [any]
triggers: [iterate, thesaurus, word swap, title variants]
path: tools/brainstorm/iterate.md
summary: One title or topic — riff a single word slot with synonyms, negatives, and wild swaps.
```

```yaml
id: hooks
name: Hooks
category: brainstorm
mode: batch
inputs: [title]
platforms: [any]
triggers: [hooks, hook variants, openings]
path: tools/brainstorm/hooks.md
summary: Same one video — many different hooks only.
```

```yaml
id: scopedown
name: Scopedown
category: brainstorm
mode: batch
inputs: [title]
platforms: [any]
triggers: [scopedown, scope down, process steps, filmable parts]
path: tools/brainstorm/scopedown.md
summary: One title or idea per process step — resist the full-outline mega-video.
```

```yaml
id: memento-mori
name: Memento Mori
category: brainstorm
mode: interactive
inputs: [concept]
platforms: [any]
triggers: [memento mori, deathbed, regret, last thing unsaid]
path: tools/brainstorm/memento-mori.md
summary: Deathbed regret chain — map each truth to a video idea you'd finally say.
```

```yaml
id: worst-critic
name: Worst Critic
category: brainstorm
mode: interactive
inputs: [concept]
platforms: [any]
triggers: [worst critic, part x, stutz, prove it, harsh criticism]
path: tools/brainstorm/worst-critic.md
summary: Face the harshest criticism — then make proof-oriented video ideas, not reassurance.
```

---

## Channels

Slash commands: `/` + `id`. Require user expertise or topic before generating.

```yaml
id: mrbeast
name: MrBeast
category: channels
mode: batch
slash: /mrbeast
inputs: [expertise, topic]
platforms: [youtube]
triggers: [mrbeast, /mrbeast, beast, stakes, last to leave]
path: tools/channels/mrbeast.md
summary: Transpose Beast title grammar — stakes, money, scale — onto your expertise.
```

```yaml
id: veritasium
name: Veritasium
category: channels
mode: batch
slash: /veritasium
inputs: [expertise, topic]
platforms: [youtube]
triggers: [veritasium, /veritasium, curiosity gap, explain]
path: tools/channels/veritasium.md
summary: Transpose Veritasium patterns — curiosity gap, weird fact, explain — onto your topic.
```

```yaml
id: answer-in-progress
name: Answer in Progress
category: channels
mode: batch
slash: /answer-in-progress
inputs: [expertise, topic]
platforms: [youtube]
triggers: [answer in progress, /answer-in-progress, whimsical why]
path: tools/channels/answer-in-progress.md
summary: Whimsical why + prove-a-point process titles for your domain.
```

```yaml
id: ryan-trahan
name: Ryan Trahan
category: channels
mode: batch
slash: /ryan-trahan
inputs: [expertise, topic]
platforms: [youtube]
triggers: [ryan trahan, /ryan-trahan, quest, i did this]
path: tools/channels/ryan-trahan.md
summary: Earnest I-did-this quest titles applied to your craft or topic.
```

```yaml
id: super-simple-songs
name: Super Simple Songs
category: channels
mode: batch
slash: /super-simple-songs
inputs: [expertise, topic]
platforms: [youtube]
triggers: [super simple songs, /super-simple-songs, singable, kids songs]
path: tools/channels/super-simple-songs.md
summary: Ultra-simple singable loop patterns for your teachable topic.
```

```yaml
id: cocomelon
name: Cocomelon
category: channels
mode: batch
slash: /cocomelon
inputs: [expertise, topic]
platforms: [youtube]
triggers: [cocomelon, /cocomelon, toddler clarity, routine]
path: tools/channels/cocomelon.md
summary: Toddler-max clarity and routine-song title patterns for your subject.
```

```yaml
id: yoga-with-adriene
name: Yoga With Adriene
category: channels
mode: batch
slash: /yoga-with-adriene
inputs: [expertise, topic]
platforms: [youtube]
triggers: [yoga with adriene, /yoga-with-adriene, find what feels good]
path: tools/channels/yoga-with-adriene.md
summary: Gentle timed-practice title patterns — beginner-friendly, body-specific.
```

```yaml
id: phlearn
name: Phlearn
category: channels
mode: batch
slash: /phlearn
inputs: [expertise, topic]
platforms: [youtube]
triggers: [phlearn, /phlearn, how to, technique]
path: tools/channels/phlearn.md
summary: Clear how-to technique titles — one skill, one video.
```

```yaml
id: fireship
name: Fireship
category: channels
mode: batch
slash: /fireship
inputs: [expertise, topic]
platforms: [youtube]
triggers: [fireship, /fireship, 100 seconds, code report]
path: tools/channels/fireship.md
summary: Compressed witty tech title patterns — fast hook, opinion, demo.
```

```yaml
id: 5-minute-crafts
name: 5-Minute Crafts
category: channels
mode: batch
slash: /5-minute-crafts
inputs: [expertise, topic]
platforms: [youtube, tiktok]
triggers: [5 minute crafts, /5-minute-crafts, hacks, numbered list]
path: tools/channels/5-minute-crafts.md
summary: Rapid numbered visual hack title patterns for your niche.
```

```yaml
id: programming-with-mosh
name: Programming with Mosh
category: channels
mode: batch
slash: /programming-with-mosh
inputs: [expertise, topic]
platforms: [youtube]
triggers: [programming with mosh, /programming-with-mosh, full course, beginner]
path: tools/channels/programming-with-mosh.md
summary: Clean full beginner course title patterns for your teachable skill.
```

```yaml
id: theprimeagen
name: ThePrimeagen
category: channels
mode: batch
slash: /theprimeagen
inputs: [expertise, topic]
platforms: [youtube]
triggers: [theprimeagen, /theprimeagen, prime, hot take, live craft]
path: tools/channels/theprimeagen.md
summary: High-energy eng opinion + live craft title patterns for your domain.
```

---

## From-source

Category stub — no implemented tools in v1. Future inputs: video, transcript, article, text, Ansaur CSV.

See [tools/from-source/_CATEGORY.md](tools/from-source/_CATEGORY.md).

---

## Team

Category stub — no implemented tools in v1. Future: multiplayer workshop facilitation.

See [tools/team/_CATEGORY.md](tools/team/_CATEGORY.md).
