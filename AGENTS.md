# Agent Guidelines (AGENTS.md)

This document outlines how Claude Code and any other AI agents should approach contributions to this repository.

## General Principles

1. **Respect project boundaries** – When working on a specific user's code, limit modifications to that user's folder only. Do not edit other users' directories unless explicitly instructed.
2. **Write tests** – Every piece of generated code must be accompanied by appropriate unit/integration tests.
3. **Maintain readability** – Follow the project's coding style (use existing linting/configuration) and keep changes minimal and clear.
4. **Communicate intent** – When making non‑trivial changes, add concise commit messages and inline comments explaining the rationale.
5. **Handle secrets responsibly** – All secrets used by a user must be stored in a `.env` file inside that user's folder (unless the user explicitly states otherwise). Secrets must never appear in commit messages, code files, or any published artifacts.
6. **Attribution for generated work** – PRs, commits, and comments created by an AI agent must be signed, indicating which model co‑authored the change and which skill/agent was used. This attribution should appear in the commit message or PR description to clarify the source of generated code.

## Specific Agent Tasks

- **Claude Code**: Primarily used for code generation, refactoring, and providing explanations. Always double‑check generated output against existing tests and style guidelines.
- **Other agents** (e.g., static analysis bots): Run automatically on pull requests to enforce linting, test coverage, and dependency hygiene.

By adhering to these guidelines, agents help maintain a safe and educational environment for workshop participants.
