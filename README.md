# Obsidian Doc Writer

Codex plugin for writing technical documentation inside an existing Obsidian vault.

It stays Markdown-first, uses Mermaid for inline diagrams, switches to JSON Canvas when layout matters, and uses Obsidian Bases for structured documentation indexes.

## What It Adds

- One skill: `obsidian-doc-writer`
- Routing for `.md`, Mermaid, `.canvas`, and `.base`
- Templates for module docs, ADRs, runbooks, and API notes
- Existing-vault-only scope to avoid unwanted scaffolding

## Install

From a local clone:

```bash
codex plugin marketplace add .
codex plugin add obsidian-doc-writer@obsidian-doc-writer
```

From GitHub:

```bash
codex plugin marketplace add parmcoder/obsidian-doc-writer
codex plugin add obsidian-doc-writer@obsidian-doc-writer
```

## Example Prompts

- `Write an ADR for choosing Mermaid over Canvas for this flow.`
- `Create a module doc for the auth service and link related notes.`
- `Build a docs index base for all runbooks and ADRs in this vault.`
- `Turn this architecture sketch into a Canvas board.`

## Repository Layout

```text
.agents/plugins/marketplace.json
plugins/obsidian-doc-writer/.codex-plugin/plugin.json
plugins/obsidian-doc-writer/skills/obsidian-doc-writer/SKILL.md
```
