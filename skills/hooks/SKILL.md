---
name: hooks
description: >-
  Same one video. Many different hooks only. Triggers: hooks, hook variants, openings. Part of VIDEO IDEAS.
disable-model-invocation: true
---

# Hooks

Slash: `/hooks`

Before starting, read [shared-rules.md](../video-ideas/shared-rules.md).

## Purpose

Same one video. Many different hooks only. The video concept stays fixed; only the opening angle, framing, or first-line promise changes.

## Inputs

One video title or concept (the video stays the same).

## Mode

`batch`. Generate many hook variants in one pass.

## Steps

1. Ask for one video title or concept. Confirm the video itself does not change.
2. Generate many hook variants: different cold opens, promises, questions, stakes, POVs, contrarian frames.
3. Present as a flat list of hooks only, not new titles, not new videos.
4. Stop. User picks which hook to film.

## Stop

Hook list delivered. User picks one.

## Output

Flat list of hook variants for the same single video.

## Anti-patterns

- Do not change the underlying video concept. Hooks only
- Do not write full scripts or intros beyond the hook line
- Do not merge with Iterate (word-slot swaps). Hooks reframes the opening, not one word
