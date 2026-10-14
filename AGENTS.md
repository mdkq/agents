# Introduction

This file guides agents working in this repo. Each section is a heading, an opening line stating what the section holds, its test for what gets in, and its entry format, then a list of entries; follow each section's conventions exactly. Keep this file current on your own: add entries that pass their section's test and that an agent would otherwise get wrong, and prune what's stale. Never add, rename, or remove sections, or edit this introduction, unless asked.

# Rules

Catch-all for imperative directives on how to work in this repo: behavior, boundaries, workflow. One short imperative per line. Edit only when asked.

- Write tests, comments, docs, or markdown only when asked.

# Modules

Business logic lives in deep modules, imported only through their root files; entry points such as routes stay thin. List every module here in the same change that adds or alters it. Format: `` `module` — what it does and what it hides. ``

# Commands

The one canonical command for each recurring task: set up, build, test, lint, run, and deploy. Format: `Purpose: command`

# Stack

Tools that shape how code is written across the repo, with agent-friendly docs (prefer llms.txt or markdown) and MCP servers. Format: `Tool — purpose. Docs: <url>. MCP: <server or none>.`

# Ubiquitous Language

Domain vocabulary; use these terms in conversation and code. Add a term when code or discussion names a domain concept, and skip technical terms. Format: `Term — definition. Avoid: synonyms.`

# Decisions

Settled choices, so they aren't reopened. Record a choice the human makes or approves as soon as it's made, if it's hard to reverse and a future agent would otherwise question it; mark superseded entries instead of deleting them. Format: `YYYY-MM-DD — decision.`
