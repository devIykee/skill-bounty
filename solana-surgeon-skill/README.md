# solana-surgeon-skill

**Author:** devIykee

**Repo:** https://github.com/deviykee/solana-surgeon-skill

**Type:** New skill (novel idea)

## What it does

A surgical reasoning meta-skill for Claude Code agents on Solana.

Installs five disciplines into any agent working on Solana:

1. Trace before act — SURGEON TRACE on every output
2. Diagnose before fix — 5-step diagnosis before any code change
3. Preflight before execution — account/PDA/tx checklists
4. Gate before destruction — stop-and-verify before irreversible ops
5. Anchor vs native awareness — correct ruleset per framework

## Files

21 files across skill/, agents/, commands/, rules/

Progressive loading — token-efficient, routes via SKILL.md

## Compatibility

Anchor 0.30+, native programs, Solana 1.18+ / Agave, Claude Code

## License

MIT
