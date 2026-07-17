# Skill template

Each VIDEO IDEAS rail is its own skill. Tool source lives at `skills/video-ideas/tools/<category>/<id>.md`. Add a matching catalog entry.

- Brainstorm → `skills/<id>/SKILL.md`
- Channels → `skills/channels/<id>/SKILL.md`

```markdown
---
name: skill-id
description: >-
  One sentence: what this skill does. Include triggers so the agent can match.
  End with "Part of VIDEO IDEAS."
disable-model-invocation: true
---

# Skill Name

Slash: `/skill-id` (brainstorm skills) or `/channel-id` (channel mimics)

Before starting, read [shared-rules.md](../video-ideas/shared-rules.md) (channels: `../../video-ideas/shared-rules.md`).

[paste Purpose, Inputs, Mode, Steps, Stop, Output, Anti-patterns from tool file]
```

**Rules**

- `name` = catalog `id` = kebab-case directory name.
- Brainstorm skills get `slash: /<id>` in catalog (e.g. `/hooks`, `/scopedown`).
- Channel skills keep creator slashes (`/mrbeast`, `/veritasium`, …).
- Target under 80 lines per skill file.
- **Anti-patterns** required.
- Do not duplicate [formats.md](formats.md) — link when relevant.
