---
id: iterate
name: Iterate
category: brainstorm
mode: batch
inputs: [title]
---

# Iterate

## Purpose

One title or topic. Iterate a single word slot: thesaurus + negatives + crazy words; many variants.

## Inputs

One title or topic seed.

## Mode

`batch`. Generate many variants in one pass; user picks favorites.

## Steps

1. Ask for one title or topic seed.
2. Identify the slot to iterate (usually the most interesting noun or verb; confirm with user if ambiguous).
3. Generate variants: synonyms, antonyms/negatives, adjacent domain terms, unexpected/crazy swaps.
4. Present as a flat list of title variants. Stop. User picks.

## Stop

Variant list delivered. User picks which to develop (Hooks, Scope Down optional).

## Output

Flat list of title variants. Same skeleton, different slot fills.

## Anti-patterns

- Do not rewrite the whole title structure each time. Iterate **one slot**
- Do not produce scripts or outlines
- Do not merge with Hooks (that's different hooks for one video, not word swaps)
