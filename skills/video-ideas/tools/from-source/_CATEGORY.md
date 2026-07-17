# From-source category

Turn existing assets into video idea sparks. **No implemented tools in v1** — this stub defines inputs and future tool names.

## Inputs (future)

| Input | Description |
|-------|-------------|
| `video` | Existing video URL or file — mine topics, gaps, comment themes |
| `transcript` | Transcript text — pull quotable moments, unanswered threads |
| `article` | Blog post or doc — extract teachable slices |
| `text` | Raw notes, email, thread — find filmable angles |
| `ansaur-csv` | [Ansaur.com](https://ansaur.com) export — real Google questions with monthly search counts |

## Ansaur CSV workflow (manual v1)

1. Export questions from [Ansaur.com](https://ansaur.com) for your topic.
2. Drop the CSV or paste the question list into the chat.
3. Pick high-volume or gap-ranked questions.
4. Run existing tools on selections: **Hooks**, **Iterate**, **Scopedown**, or slot into a **format** from [formats.md](../../formats.md).

VIDEO IDEAS facilitates; Ansaur supplies demand-backed questions — not AI-invented prompts.

## Future tools (placeholders)

| id (planned) | Summary |
|--------------|---------|
| `transcript-miner` | Pull video ideas from a transcript — quotable beats, tangents, unanswered threads |
| `article-slicer` | One article → many filmable slices (Scopedown-style) |
| `comment-reader` | Mine comment themes from a video URL into reply-video ideas |
| `ansaur-queue` | Ingest Ansaur CSV → ranked question queue → Hooks per row |
| `competitor-gap` | Compare your catalog vs a source list — surface missing pillars |
| `clip-finder` | Long video → timestamped clip ideas for Shorts/Reels |

## Contributing

When adding a from-source tool: create `tools/from-source/<id>.md`, add catalog entry, optional example in [examples.md](../../examples.md).
