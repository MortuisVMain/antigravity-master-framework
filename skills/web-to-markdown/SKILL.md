---
name: web-to-markdown
description: "Use ONLY when the user explicitly says: 'use the skill web-to-markdown ...' (or 'use a skill web-to-markdown ...'). Converts webpage URLs to clean Markdown by calling the local web2md CLI (Puppeteer + Readability), suitable for JS-rendered pages."
metadata:
  version: 0.1.0
---

# web-to-markdown

Convert web pages to clean Markdown by driving a locally installed browser (via `web2md`).

## Hard trigger gate (must enforce)

This skill MUST NOT be used unless the user explicitly wrote **exactly** a phrase like:
- `use the skill web-to-markdown ...`
- `use a skill web-to-markdown ...`

If the user did not explicitly request this skill by name, stop and ask them to re-issue the request including: `use the skill web-to-markdown`.

## What this skill does

- Handles JS-rendered pages (Puppeteer в†’ user Chrome).
- Works best with Chromium-family browsers (Chrome/Chromium/Brave/Edge) via `puppeteer-core`.
- Extracts main content (Readability).
- Converts to Markdown (Turndown) with cleaned links and optional YAML frontmatter.

## Non-goals

- Do not use Playwright or other browser automation stacks; the mechanism is `web2md`.

## Inputs you should collect (ask only if missing)

- `url` (or a list of URLs)
- Output preference:
  - Print to stdout (`--print`), OR
  - Save to a file (`--out ./file.md`), OR
  - Save to a directory (`--out ./some-dir/` to auto-name by page title)
- Optional rendering controls for tricky pages:
  - `--chrome-path <path>` (if Chrome auto-detection fails)
  - `--interactive` (show Chro

