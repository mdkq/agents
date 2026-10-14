# Introduction

This file guides agents working in this repo. Each section is a heading, an opening line stating its purpose and conventions, then a list of entries; follow each section's conventions exactly. Keep this file current: update sections per their conventions, add only what an agent would otherwise get wrong, and prune what's stale. Never add, rename, or remove sections, or edit this introduction, unless asked.

# Rules

Catch-all for imperative directives on how to work in this repo: behavior, boundaries, workflow. One short imperative per line. Edit only when asked.

- Never write tests, comments, docs, or markdown unless asked.

# Modules

Business logic lives in deep modules, imported only through their root files; entry points such as routes stay thin. List every module here in the same change that adds or alters it. Format: `` `module` — what it does and what it hides. ``

# Commands

Exact commands to set up, build, test, lint, run, and deploy. Format: `Purpose: command`

# Stack

Major tools, with agent-friendly docs (prefer llms.txt or markdown) and MCP servers. Skip minor libraries. Format: `Tool — purpose. Docs: <url>. MCP: <server or none>.`

# Ubiquitous Language

Shared domain vocabulary. Use these terms consistently in conversation and code. For a concept with no entry, propose terms. Format: `Term — definition. Avoid: synonyms.`

# Decisions

Settled choices, so they aren't reopened. Add one only when the human decides in discussion; mark superseded entries instead of deleting them. Format: `YYYY-MM-DD — decision.`
