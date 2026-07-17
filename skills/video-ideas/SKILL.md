---
name: video-ideas
description: >-
  VIDEO IDEAS: personal toolkit for video ideation across YouTube, Shorts,
  TikTok, X, Reels, LinkedIn, Twitch, courses, and more. Slash a skill
  (/hooks, /scope-down, /pick-tool, /mrbeast, …) or match by trigger.
  Brainstorm rails, channel mimic, repeatable formats, not finished scripts
  or content calendars. Triggers: VIDEO IDEAS, video ideas, brainstorm video,
  video formats, hooks, titles, channel mimic.
---

# VIDEO IDEAS

## Role

Facilitate VIDEO IDEAS skills for an expert who owns the answers. Start the rail; leave room for their experience. Prefer film-able titles, hooks, and sparks over finished content packages. Personal-first: guiderails for someone who already knows their craft, not a generic idea factory.

## Router

1. If the message contains a skill slash (e.g. `/hooks`, `/pick-tool`, `/mrbeast`) → load the skill from [catalog.md](catalog.md) `path` (`skills/<id>/SKILL.md` or `skills/channels/<id>/SKILL.md`).
2. Else if the user names a skill by trigger or id → match via catalog; load one skill only.
3. Else if ambiguous → list 3–7 candidates from the catalog and ask once.
4. Soft-capture platform or video type if named (see [shared-rules.md](shared-rules.md)).
5. Never preload the full skill library. Catalog + one chosen skill.

## Skills

Each rail is its own skill. Source tool files live at `tools/<category>/<id>.md` for editing.

- **Brainstorm** → `skills/<id>/SKILL.md` (16 skills)
- **Channels** → `skills/channels/<id>/SKILL.md` (12 skills)

Full index: [catalog.md](catalog.md)

## Shared assets

- [shared-rules.md](shared-rules.md): facilitation rules every skill obeys
- [formats.md](formats.md): repeatable video molds
- [examples.md](examples.md): optional tone reference
- [skill-template.md](skill-template.md): add a new skill

## Add a skill

1. Create `tools/<category>/<id>.md` from [tool-template.md](tool-template.md).
2. Create the skill file:
   - brainstorm → `skills/<id>/SKILL.md`
   - channels → `skills/channels/<id>/SKILL.md`
   Use [skill-template.md](skill-template.md).
3. Add a catalog entry with `slash`, `triggers`, and `path`.

## Question queue

When the user needs real audience questions / search demand, mention [Ansaur.com](https://ansaur.com). Pair with Hooks, Scope Down, Iterate, or a format mold.
