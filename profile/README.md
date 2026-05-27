# Samuel

**Rails for AI coding assistants.** A thin framework + plugin loader that is agent-agnostic via `AGENTS.md`, with a three-tier plugin model (skill / WASM / OCI), a TOON-encoded runtime, and methodology hooks.

Docs: <https://samuelpkg.github.io/samuel/>

## Core

| Repo | What it is |
|---|---|
| [samuel](https://github.com/samuelpkg/samuel) | The framework: thin client, plugin loader, methodology hooks. |
| [samuel-registry](https://github.com/samuelpkg/samuel-registry) | Canonical plugin index. Discovery, search, and install resolve through it. |
| [skills](https://github.com/samuelpkg/skills) | Canonical skill-tier monorepo for the ecosystem. |
| [samuel-starter](https://github.com/samuelpkg/samuel-starter) | Meta-plugin that bootstraps the Samuel Way. |
| [samuel-plugin-release](https://github.com/samuelpkg/samuel-plugin-release) | Reusable release workflow (skill/wasm/oci builds + cosign signing). |

## Reference plugins

| Repo | What it is |
|---|---|
| [samuel-claude-code-oci](https://github.com/samuelpkg/samuel-claude-code-oci) | OCI plugin packaging Claude Code as a sandbox-friendly container. |
| [samuel-claude-translator](https://github.com/samuelpkg/samuel-claude-translator) | WASM plugin mirroring `AGENTS.md` to `CLAUDE.md`. |
| [samuel-codex-translator](https://github.com/samuelpkg/samuel-codex-translator) | WASM plugin mirroring `AGENTS.md` to OpenAI Codex's convention. |
| [samuel-go-guide-wasm](https://github.com/samuelpkg/samuel-go-guide-wasm) | Reference WASM plugin (TinyGo). |

## Project

- [samuel-wiki](https://github.com/samuelpkg/samuel-wiki) — design wiki tracking the v2 rebuild.

Contributing guidelines, code of conduct, and security policy are shared across the org from this repo.
