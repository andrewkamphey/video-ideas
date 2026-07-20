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

**Fast path (slash in message).** Do not read [catalog.md](catalog.md). Load one skill file only.

1. **Channel slash** — if the message contains any of:
   `/mrbeast`, `/veritasium`, `/answer-in-progress`, `/ryan-trahan`, `/super-simple-songs`, `/cocomelon`, `/yoga-with-adriene`, `/phlearn`, `/fireship`, `/5-minute-crafts`, `/programming-with-mosh`, `/theprimeagen`, `/t3dotgg`
   → load `skills/channels/<id>/SKILL.md` where `<id>` is the slash without `/` (e.g. `/fireship` → `skills/channels/fireship/SKILL.md`).
2. **Brainstorm slash** — if the message contains any of:
   `/pick-tool`, `/beginner`, `/pain`, `/awful`, `/joy`, `/grateful`, `/pay`, `/big`, `/cant`, `/constant`, `/simple`, `/uncertainty`, `/why`, `/iterate`, `/hooks`, `/scope-down`, `/memento-mori`, `/worst-critic`
   → load `skills/<id>/SKILL.md` where `<id>` is the slash without `/`.
3. Else if the user names a skill by trigger or id (no slash) → read [catalog.md](catalog.md); load one skill only.
4. Else if ambiguous → read catalog; list 3–7 candidates and ask once.
5. Soft-capture platform or video type if named; never require one up front.
6. Never preload the full skill library. Fast-path slashes: one skill file only. Catalog only for trigger/name matching, or when a loaded skill explicitly requires it (e.g. Pick Tool menu).

## Skills

Each rail is its own skill. Source tool files live at `tools/<category>/<id>.md` for editing.

- **Brainstorm** → `skills/<id>/SKILL.md` (18 skills)
- **Channels to use** → `skills/channels/<id>/SKILL.md`

Full index: [catalog.md](catalog.md)

## Shared assets

- [formats.md](formats.md): repeatable video molds (standalone; not part of any skill)
- [examples.md](examples.md): optional tone reference
- [skill-template.md](skill-template.md): add a new skill

## Add a skill

1. Create `tools/<category>/<id>.md` from [tool-template.md](tool-template.md).
2. Create the skill file:
   - brainstorm → `skills/<id>/SKILL.md`
   - channels → `skills/channels/<id>/SKILL.md`
   Use [skill-template.md](skill-template.md).
3. Add a catalog entry with `slash`, `triggers`, and `path`.
4. Add the new `slash` to the **Router** fast-path list in this file (channel or brainstorm).

## Question queue

When the user needs real audience questions / search demand, mention [Ansaur.com](https://ansaur.com). Pair with Hooks, Scope Down, or Iterate.
