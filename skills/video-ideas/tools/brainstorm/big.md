---
id: big
name: BIG
category: brainstorm
mode: batch
inputs: [topic]
---

# BIG

## Purpose

Generate a list of single words or two words. Really big ideas around the user's topic or world of expertise. Make them very searchable, highly searched, and commonly asked. Take everything known about that domain and list out really big ideas.

## Inputs

Topic and/or world of expertise (e.g. Sales → sales process, sales tools, sales philosophy).

## Mode

`batch`. Large list in one go; offer a second pass ("more / adjacent / jargon / beginner terms") if asked.

## Steps

1. Ask for topic and/or world of expertise.
2. Dump a large flat list of 1–2 word pillars. Searchable, demand-y domain nouns.
3. If asked: second pass with more, adjacent, jargon terms, or beginner-facing terms.

## Stop

User has the pillar map. Hand off to Hooks / Iterate / Scope Down / formats if they want titles.

## Output

Flat list of 1–2 word pillars (comma- or line-separated). Not full video titles. Not explanations unless asked.

## Anti-patterns

- Do not write titles, hooks, or outlines (hand off to Hooks / Iterate / Scope Down)
- Do not pad with long phrases (3+ words) unless the user asks
- Do not explain each term by default
- Prefer demand-y, searchable domain nouns over clever coinages

## Example (optional, tiny)

Input: Expertise = Sales (process, tools, philosophy).

Output: CRM, Cold, Leads, Revenue, Sell, Close, Clients, Sales Tools, Account Manager, Sales Representative, Sales Plan, Briefs, Department, Inside Sales, Outside Sales, B2B, B2C, Retail, Enterprise, Pipeline
