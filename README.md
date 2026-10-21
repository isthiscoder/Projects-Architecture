# Project Architecture

End to end architecture of my projects explained (how I build). Live at [architecture.isidd.dev](https://architecture.isidd.dev).
Live demos: [projects.isidd.dev](https://projects.isidd.dev) · How the technology works: [playbook.isidd.dev](https://playbook.isidd.dev)

## How it works
- **Home page:** every write-up, newest first, **12 per page**. Older ones continue on `/page2/`, `/page3/` and so on, with page numbers and Newer / Older links.
- **Each write-up** opens its own page at `architecture.isidd.dev/<title>/`, with the date, reading time and author (Siddharth Singh) at the top.
- **Search** in the top bar looks through every write-up's title, tags and date.
- Black on white, EB Garamond only, no italics (monospace is used inside code blocks).

## Add a write-up
Create `_posts/YYYY-MM-DD-project-name.md`:

```markdown
---
layout: post
title: "Travel Experience Agent: how I built it"
subtitle: "One-line summary"   # optional
tags: [AI, agents, system design]
read: 15                       # optional, otherwise counted automatically
---

## The problem
## Architecture
## Key decisions
## What I'd do differently
```

The file name decides the address: `2026-12-20-travel-experience-agent.md` → `architecture.isidd.dev/travel-experience-agent/`.
Always close the top block with `---` on its own line.

Fonts: EB Garamond (SIL OFL, self-hosted). MIT [LICENSE](LICENSE).
