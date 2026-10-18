# AI-Global-Skills

Global Cursor skills available in every project on the machine.

These skills are installed with the `--global` flag so they live in the user skills folder (`~/.cursor/skills/` or equivalent) and are usable across all repositories.

## What’s included

| Skill | Source | Purpose |
|-------|--------|---------|
| `unslop` | [pstack](https://github.com/cursor/plugins) | Remove AI writing patterns and clean up generated text (docs, PR descriptions, comments). |

## How to install

Run once per machine (from any directory):

```bash
npx skills add https://github.com/MichaelB14/AI-Global-Skills --global
