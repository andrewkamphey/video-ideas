---
name: iterate
description: >-
  One title or topic — riff a single word slot with synonyms, negatives, and wild swaps. Triggers: iterate, thesaurus, word swap, title variants. Part of VIDEO IDEAS.
disable-model-invocation: true
---

# Iterate

Slash: `/iterate`

Before starting, read [shared-rules.md](../video-ideas/shared-rules.md).

## Purpose

One title or topic — iterate a single word slot: thesaurus + negatives + crazy words; many variants.

## Inputs

One title or topic seed.

## Mode

`batch` — generate many variants in one pass; user picks favorites.

## Steps

1. Ask for one title or topic seed.
2. Identify the slot to iterate (usually the most interesting noun or verb — confirm with user if ambiguous).
3. Generate variants: synonyms, antonyms/negatives, adjacent domain terms, unexpected/crazy swaps.
4. Present as a flat list of title variants. Stop. User picks.

## Stop

Variant list delivered. User picks which to develop (Hooks, Scopedown, formats optional).

## Output

Flat list of title variants — same skeleton, different slot fills.

## Anti-patterns

- Do not rewrite the whole title structure each time — iterate **one slot**
- Do not produce scripts or outlines
- Do not merge with Hooks (that's different hooks for one video, not word swaps)
