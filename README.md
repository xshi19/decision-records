# Decision Records

A Cursor plugin for recording durable engineering decisions (ADRs) and recovering them before design changes.

## Skill

- [`adr`](skills/adr/SKILL.md): use when recording a consequential choice or an inconclusive alternative, or when checking prior decisions before proposing a design change. It reuses the repository's existing ADR format; [references/template.md](skills/adr/references/template.md) is a minimal fallback skeleton.

The agent picks the skill automatically from its description, or you can invoke it with `/adr` in chat.

If pstack is installed, run its `why` skill first when asked why a design was chosen, to find the existing record.

## Install

Install from the Cursor Marketplace, or for local testing copy this directory to `~/.cursor/plugins/local/decision-records` and reload the window. No configuration is required.

## License

[MIT](LICENSE)
