# patrickwiloak (GitHub profile README)

## Overview
The special `PatrickWiloak/patrickwiloak` repository whose `README.md` renders as the
GitHub profile page for the user PatrickWiloak. It is a presentation surface - bio,
experience, tech-stack/certification badges, and social links - not an application. Edit
`README.md` to change what visitors see at github.com/PatrickWiloak.

## Environment
- **Status**: Live profile page (public repo)
- **Live URL**: https://github.com/PatrickWiloak
- **Cloud**: N/A (rendered by GitHub)

## Tech Stack
- Markdown + shields.io badges + a readme-typing-svg animated header; `banner.jpg` asset.
- No build system, no source code.

## Common Commands
None - edit `README.md` directly. Pushing to the default branch updates the live profile.

## Project Structure
```
README.md     the rendered profile (bio, experience, badges, links)
banner.jpg    header banner image
```
Note: `graphify-out/` is gitignored here (public repo - graphs stay local).

## graphify

This project has a knowledge graph at graphify-out/ with god nodes, community structure, and cross-file relationships.

Rules:
- For codebase questions, first run `graphify query "<question>"` when graphify-out/graph.json exists. Use `graphify path "<A>" "<B>"` for relationships and `graphify explain "<concept>"` for focused concepts. These return a scoped subgraph, usually much smaller than GRAPH_REPORT.md or raw grep output.
- If graphify-out/wiki/index.md exists, use it for broad navigation instead of raw source browsing.
- Read graphify-out/GRAPH_REPORT.md only for broad architecture review or when query/path/explain do not surface enough context.
- After modifying code, run `graphify update .` to keep the graph current (AST-only, no API cost).
