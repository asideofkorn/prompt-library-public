# prompt-library-public

A small, **read-only-by-design** prompt library for showcasing prompt craft: structure, tone control, and repeatable results.  
This repo is intended to be easy to browse, fork, and reuse.

## Philosophy

- **Prompts are products:** clear inputs, clear outputs, explicit constraints.
- **Separation of concerns:** prompts reference reusable **context** instead of duplicating it.
- **Portable:** plain Markdown, minimal tooling, works anywhere.
- **Safe & non-proprietary:** no company-specific or sensitive content.

## Repo Structure

- `prompts/<domain>/<prompt_slug>/v###.md` — versioned prompts
- `contexts/<domain>/<context_slug>.md` — reusable context blocks
- `examples/` — sanitized inputs/outputs (small, illustrative)

## Versioning

- Prompts are versioned as files: `v001.md`, `v002.md`, ...
- **Each version is immutable** (create a new version rather than editing old ones).
- Git history provides the audit trail and change rationale.

## Examples

- Browse prompts: `prompts/`
- Browse context blocks: `contexts/`
- See rendered examples: `examples/`

## Contributions

This repository is **read-only to the public**.  
If you want to suggest an improvement, please **fork** the repo and open a **pull request** with context.

## License

MIT
