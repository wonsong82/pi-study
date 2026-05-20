# Project Instructions

This repo is a personal study/reference project for learning pi coding agent concepts.

## Main goal

Maintain clear, navigable documentation that explains how pi works, especially:

- system prompt construction
- AGENTS.md / SYSTEM.md / APPEND_SYSTEM.md behavior
- extensions, skills, prompt templates, themes, packages
- built-in tools vs active tools
- example extensions, especially plan-mode

## Documentation convention

When creating or updating HTML documentation:

- Update both English and Korean versions.
- Keep paired filenames consistent:
  - English: `docs/name.html`
  - Korean: `docs/name.ko.html`
- Keep pages self-contained: inline CSS/JS/SVG is okay.
- Prefer navigable structure over long prose:
  - sidebar navigation
  - searchable sections
  - compact tables
  - collapsed `<details>` for long explanations
  - simple SVG diagrams when helpful

## Current docs

Primary reference pages:

- `docs/pi-overview.html`
- `docs/pi-overview.ko.html`

These pages should stay semantically aligned.

## Style

- Be concise but precise.
- Use simple language and explicit mental models.
- Preserve distinctions like:
  - prompt template = user-facing macro
  - skill = agent-facing capability/manual
  - extension = runtime behavior
  - registered tools = tools pi knows about
  - active tools = tools currently sent to the model

## Study findings

Put study findings, gotchas, and detailed notes directly into the docs, not in this instruction file.

## Working behavior

Before making large doc changes, explain the intended structure briefly.
Do not create unrelated app/code unless explicitly asked.
