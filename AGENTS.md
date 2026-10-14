# Introduction

This file guides agents working in this repo. Each section opens with what it contains, when to add an entry, and the format entries take; follow these exactly. Keep the file current on your own, adding only what an agent would otherwise get wrong and pruning what's stale. Never add, rename, or remove sections, or edit this introduction, unless asked.

# Rules

Contains: Imperative directives on how to work in this repo, covering behavior, boundaries, and workflow; a catch-all for what fits no other section.

Add when: The human asks for one.

Format: One short imperative per line.

- Write tests, comments, docs, or markdown only when asked.

# Modules

Contains: Deep modules, where all business logic lives; other code imports them only through their root files, and entry points such as routes stay thin.

Add when: A module is created or changed; update its entry in the same change.

Format: `` `module` — what it does and what it hides. ``

# Commands

Contains: Commands to set up, build, test, lint, run, and deploy.

Add when: A task recurs; keep one canonical command per task.

Format: `Purpose: command`

# Stack

Contains: Major tools, with agent-friendly docs (prefer llms.txt or markdown) and MCP servers.

Add when: A tool shapes how code is written across the repo.

Format: `Tool — purpose. Docs: <url>. MCP: <server or none>.`

# Ubiquitous Language

Contains: Domain vocabulary, used consistently in conversation and code.

Add when: Code or discussion names a domain concept; skip technical terms.

Format: `Term — definition. Avoid: synonyms.`

# Decisions

Contains: Settled choices, so they aren't reopened; superseded entries are marked, not deleted.

Add when: The human makes or approves a choice that's hard to reverse and that a future agent would otherwise question; add it right away.

Format: `YYYY-MM-DD — decision.`
