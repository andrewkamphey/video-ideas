# Catalog

Full index of VIDEO IDEAS skills. Grouped by category. Load **one** skill per session. Brainstorm skills live at `skills/<id>/SKILL.md`; channel skills at `skills/channels/<id>/SKILL.md`.

**Slash commands:** resolve via the Router fast path in [SKILL.md](SKILL.md) — do not read this file. Use catalog only for trigger/name matching or menus (e.g. `/pick-tool`).

## TOC

- [Brainstorm](#brainstorm): 18 skills
- [Channels](#channels): Channels to use

---

## Brainstorm

```yaml
id: pick-tool
name: Pick Tool
category: brainstorm
mode: interactive
slash: /pick-tool
inputs: [feeling, goal]
platforms: [any]
triggers: [pick tool, /pick-tool, choose skill, which tool, menu]
path: ../pick-tool/SKILL.md
summary: Ask how you feel or what you want. Suggest skills, pick one, run it.
```

```yaml
id: beginner
name: Beginner
category: brainstorm
mode: interactive
slash: /beginner
inputs: [concept, topic]
platforms: [any]
triggers: [beginner, beginner questions, socratic, naive questions, beginner list]
path: ../beginner/SKILL.md
summary: Pepper beginner questions or dump a naive question list to map the common baseline.
```

```yaml
id: pain
name: Pain
category: brainstorm
mode: interactive
slash: /pain
inputs: [concept]
platforms: [any]
triggers: [pain, bad, radical acceptance, list the pain, complaints]
path: ../pain/SKILL.md
summary: List pains bluntly. Acknowledgment, not obligatory triumph arcs.
```

```yaml
id: awful
name: Awful
category: brainstorm
mode: interactive
slash: /awful
inputs: [domain, expertise]
platforms: [any]
triggers: [awful, bad ideas, terrible ideas, couldn't happen, or would they, awe-ful]
path: ../awful/SKILL.md
summary: Countdown to 20 AWFUL video ideas. Terrible premises that become awe-ful.
```

```yaml
id: joy
name: Joy
category: brainstorm
mode: interactive
slash: /joy
inputs: [concept]
platforms: [any]
triggers: [joy, joyful, over excited, write and move on]
path: ../joy/SKILL.md
summary: Interactive countdown to 20 joys. Write it down and move on; don't marinate.
```

```yaml
id: grateful
name: Grateful
category: brainstorm
mode: interactive
slash: /grateful
inputs: [concept]
platforms: [any]
triggers: [grateful, gratitude, who helped, past self]
path: ../grateful/SKILL.md
summary: Interactive countdown to 20 grateful moments. Who, what, why, when; past-self and near-misses.
```

```yaml
id: pay
name: Pay
category: brainstorm
mode: interactive
slash: /pay
inputs: [concept]
platforms: [any]
triggers: [pay, what people pay for, revenue, transactions, sales not marketing]
path: ../pay/SKILL.md
summary: Interactive countdown to 20 real money flows. What people actually pay you for, not aspirations.
```

```yaml
id: big
name: BIG
category: brainstorm
mode: interactive
slash: /big
inputs: [topic]
platforms: [any]
triggers: [big, big ideas, pillars, searchable, domain map]
path: ../big/SKILL.md
summary: Interactive countdown to 20 searchable pillars. 1 word, or 2 word phrasesthat are big ideas in your topic or expertise, or experience.
```

```yaml
id: cant
name: CANT
category: brainstorm
mode: interactive
slash: /cant
inputs: [expertise]
platforms: [any]
triggers: [cant, can't, cannot, myths, limits, impossibilities]
path: ../cant/SKILL.md
summary: Interactive countdown to 20 cannots and domain myths. Edges of what you can and can't do.
```

```yaml
id: constant
name: Constant
category: brainstorm
mode: interactive
slash: /constant
inputs: [concept]
platforms: [any]
triggers: [constant, ongoing work, invisible load, still work]
path: ../constant/SKILL.md
summary: Interactive countdown to 20 constants. Recurring labor outsiders assume is done.
```

```yaml
id: simple
name: Simple
category: brainstorm
mode: interactive
slash: /simple
inputs: [concept]
platforms: [any]
triggers: [simple, keep it simple, givens, path of least resistance, don't overthink, automatic]
path: ../simple/SKILL.md
summary: Interactive countdown to 20 SUPER SIMPLE things. Givens, automatic habits, what anyone can do right now.
```

```yaml
id: uncertainty
name: Uncertainty
category: brainstorm
mode: interactive
slash: /uncertainty
inputs: [concept]
platforms: [any]
triggers: [uncertainty, uncertain, false certainty, unknown unknowns]
path: ../uncertainty/SKILL.md
summary: Interactive countdown to 20 uncertainties. What stays unresolved and what people wrongly treat as settled.
```

```yaml
id: why
name: Why
category: brainstorm
mode: interactive
slash: /why
inputs: [concept]
platforms: [any]
triggers: [why, why chain, 5 whys, five whys]
path: ../why/SKILL.md
summary: Dig five layers of why to sharpen a video idea.
```

```yaml
id: iterate
name: Iterate
category: brainstorm
mode: batch
slash: /iterate
inputs: [title]
platforms: [any]
triggers: [iterate, thesaurus, word swap, title variants]
path: ../iterate/SKILL.md
summary: One title or topic. Riff a single word slot with synonyms, negatives, and wild swaps.
```

```yaml
id: hooks
name: Hooks
category: brainstorm
mode: batch
slash: /hooks
inputs: [title]
platforms: [any]
triggers: [hooks, hook variants, openings]
path: ../hooks/SKILL.md
summary: Same one video. Many different hooks only.
```

```yaml
id: scope-down
name: Scope Down
category: brainstorm
mode: batch
slash: /scope-down
inputs: [title]
platforms: [any]
triggers: [scope-down, scope down, process steps, filmable parts]
path: ../scope-down/SKILL.md
summary: One title or idea per process step. Resist the full-outline mega-video.
```

```yaml
id: memento-mori
name: Memento Mori
category: brainstorm
mode: interactive
slash: /memento-mori
inputs: [concept]
platforms: [any]
triggers: [memento mori, deathbed, regret, last thing unsaid]
path: ../memento-mori/SKILL.md
summary: Deathbed regret chain. Map each truth to a video idea you'd finally say.
```

```yaml
id: worst-critic
name: Worst Critic
category: brainstorm
mode: interactive
slash: /worst-critic
inputs: [concept]
platforms: [any]
triggers: [worst critic, part x, stutz, prove it, harsh criticism]
path: ../worst-critic/SKILL.md
summary: Face the harshest criticism. Then make proof-oriented video ideas, not reassurance.
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
path: ../channels/mrbeast/SKILL.md
summary: Transpose Beast title grammar (stakes, money, scale) onto your expertise.
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
path: ../channels/veritasium/SKILL.md
summary: Transpose Veritasium patterns (curiosity gap, weird fact, explain) onto your topic.
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
path: ../channels/answer-in-progress/SKILL.md
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
path: ../channels/ryan-trahan/SKILL.md
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
path: ../channels/super-simple-songs/SKILL.md
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
path: ../channels/cocomelon/SKILL.md
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
path: ../channels/yoga-with-adriene/SKILL.md
summary: Gentle timed-practice title patterns. Beginner-friendly, body-specific.
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
path: ../channels/phlearn/SKILL.md
summary: Clear how-to technique titles. One skill, one video.
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
path: ../channels/fireship/SKILL.md
summary: Compressed witty tech title patterns. Fast hook, opinion, demo.
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
path: ../channels/5-minute-crafts/SKILL.md
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
path: ../channels/programming-with-mosh/SKILL.md
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
path: ../channels/theprimeagen/SKILL.md
summary: High-energy eng opinion + live craft title patterns for your domain.
```

```yaml
id: t3dotgg
name: Theo — t3.gg
category: channels
mode: batch
slash: /t3dotgg
inputs: [expertise, topic]
platforms: [youtube]
triggers: [t3dotgg, /t3dotgg, theo, t3 stack, hot take, ai workflow]
path: ../channels/t3dotgg/SKILL.md
summary: Opinionated full-stack + AI industry title patterns for your domain.
```
