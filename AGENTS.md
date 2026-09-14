# Sukarix CLI

Bash CLI application for the Sukarix framework.
Designed for Ubuntu 22.04 LTS. MIT licensed. Contributions welcome.

## What it does

`sukarix.sh` is a single-file Bash script that bootstraps and manages
Sukarix projects — creating new applications, running development servers,
clearing caches, and performing common framework tasks from the terminal.

## Quick start

```bash
./sukarix.sh          # show available commands
```

## Conventions

- Target Bash 4+ (Ubuntu 22.04 LTS default)
- Keep the script self-contained — no external Bash dependencies
- Use `set -euo pipefail` for safety
- Test commands on a clean Ubuntu 22.04 environment

## AI usage

This project is developed with AI assistance (Devin, GitHub Copilot, and others).
AI-generated contributions are welcome and should follow the same conventions as human contributions.

## Commits

One logical change per commit, described in a single-line subject: no body, no `Co-Authored-By` or other trailers.

```
Add request-id correlation and structured JSON logging
```
