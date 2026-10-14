# Introduction

This file guides agents working in this repo. Each section opens with what it contains, when to add an entry, and the format entries take. Follow these exactly. Keep the file current on your own, adding only what an agent would otherwise get wrong and pruning what's stale. Never add, rename, or remove sections, or edit this introduction, unless asked.

# Rules

**Contains:** Directives on how to work in this repo. It's the catch-all for anything that fits no other section.

**Add when:** The human asks for one.

**Format:** One short imperative per line.

- Write tests, comments, docs, or Markdown only when asked.

# Modules

**Contains:** The deep modules that hold all business logic. Other code imports a module only through its root files, and entry points such as routes stay thin.

**Add when:** A module is created or changed. Update its entry in the same change.

**Format:** `module — what it does and what it hides.`

# Commands

**Contains:** Exact commands for working in this repo.

**Add when:** A task recurs often. Keep one canonical command per task.

**Format:** `Purpose: command`

# Stack

**Contains:** Major tools, with their agent-friendly docs and MCP servers. Prefer llms.txt or Markdown docs.

**Add when:** A tool shapes how code is written across the repo.

**Format:** `Tool — purpose. Docs: <url>. MCP: <server or none>.`

# Ubiquitous Language

**Contains:** Domain vocabulary, used consistently in conversation and code.

**Add when:** Code or discussion names a domain concept. Skip technical terms.

**Format:** `Term — definition. Avoid: synonyms.`

# Decisions

**Contains:** Settled choices, so they aren't reopened.

**Add when:** The human makes or approves a hard-to-reverse choice that a future agent would otherwise question. Add it right away.

**Format:** `YYYY-MM-DD — decision.`
