# Contributing to VIDEO IDEAS

Thank you for extending the toolkit. Keep tools small, facilitation-focused, and consistent with existing terminology.

## Terminology

| Term | Meaning |
|------|---------|
| **Skill** | The skill package (`video-ideas`) |
| **Tool** | One facilitation method in the library |
| **Channel tool** | Mimic a creator's *approach* for **your** expertise |
| **Format** | A repeatable video mold—not an announced series |
| **Catalog** | Index of all tools |
| **Category** | `brainstorm` \| `channels` \| `from-source` \| `team` |

## Add a brainstorm / from-source / team tool

1. Copy [`skills/video-ideas/tool-template.md`](skills/video-ideas/tool-template.md) → `skills/video-ideas/tools/<category>/<id>.md`
2. Fill all sections; include **Anti-patterns**
3. Add a catalog entry in the right category block in [`catalog.md`](skills/video-ideas/catalog.md)
4. Optionally add a short example to [`examples.md`](skills/video-ideas/examples.md)

## Add a format

1. Append one entry to [`formats.md`](skills/video-ideas/formats.md) (skeleton + fill rule)
2. Do not frame it as a series

## Add a channel tool

1. Copy [`channel-template.md`](skills/video-ideas/channel-template.md) → `skills/video-ideas/tools/channels/<id>.md`
2. Set `slash` in frontmatter; fill short ethos + real top titles
3. Add a catalog entry

## Do not

- Edit `SKILL.md` unless you are adding a new **category**
- Preload multiple tools in one session (one tool in context at a time)
- Copy a channel's niche topics into your domain—transpose title grammar only

## File naming

- File stem = catalog `id` = kebab-case (`memento-mori.md`, `mrbeast.md`)
- Channel slash = `/` + id (`/mrbeast`, `/5-minute-crafts`)
