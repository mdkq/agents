# Introduction

This file guides agents working in this repo. Each section is a heading, three labeled lines, then a list of entries: `Holds:` states what the section contains, `Test:` the condition an entry must meet to get in, and `Format:` the shape of each entry; follow them exactly. Keep this file current on your own: add entries that pass their section's test and that an agent would otherwise get wrong, and prune what's stale. Never add, rename, or remove sections, or edit this introduction, unless asked.

# Rules

Holds: Imperative directives on how to work in this repo: behavior, boundaries, workflow; a catch-all for what fits no other section.

Test: The human asked for it.

Format: One short imperative per line.

- Write tests, comments, docs, or markdown only when asked.

# Modules

Holds: Deep modules, where all business logic lives; other code imports them only through their root files, and entry points such as routes stay thin.

Test: It is a module; update its entry in the same change that adds or alters the module.

Format: `` `module` — what it does and what it hides. ``

# Commands

Holds: Commands to set up, build, test, lint, run, and deploy.

Test: It is the one canonical command for a recurring task.

Format: `Purpose: command`

# Stack

Holds: Major tools, with agent-friendly docs (prefer llms.txt or markdown) and MCP servers.

Test: It shapes how code is written across the repo.

Format: `Tool — purpose. Docs: <url>. MCP: <server or none>.`

# Ubiquitous Language

Holds: Domain vocabulary, used consistently in conversation and code.

Test: Code or discussion names a domain concept; technical terms stay out.

Format: `Term — definition. Avoid: synonyms.`

# Decisions

Holds: Settled choices, so they aren't reopened; superseded entries are marked, not deleted.

Test: The human made or approved it, it's hard to reverse, and a future agent would otherwise question it; record it as soon as it's made.

Format: `YYYY-MM-DD — decision.`
