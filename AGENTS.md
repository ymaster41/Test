# AGENTS.md

Defines how the LLM maintains the wiki.

## Structure
- raw/: source documents (immutable)
- wiki/: generated markdown knowledge base

## Rules
- Never edit raw/
- Always update index.md and log.md after changes
- Cross-link related pages
