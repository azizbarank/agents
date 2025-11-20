# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a learning repository for exploring and implementing Claude Code agents. The project is in early stages and focuses on designing custom agent architectures.

## Project Purpose

The repository contains planning documents and design specifications for building specialized Claude Code subagents:
- **backend-architect**: Backend system and API design
- **frontend-developer**: Frontend application development
- **deployment-engineer**: CI/CD and infrastructure management
- **research-agent**: Codebase analysis and documentation research
- **executor-evaluator-loop**: Two-agent quality assurance system

These agent concepts are documented in [agent-ideas.md](agent-ideas.md) and are in the planning phase.

## Environment Setup

This project uses Python 3.13+ managed by `uv`:

```bash
# The project was initialized with uv
uv sync              # Install dependencies
uv run python main.py  # Run the main script
```

## Code Quality

Always run `ruff` before committing code:

```bash
uv run ruff check .
uv run ruff format .
```

## Architecture Notes

This is currently a minimal Python project scaffold. The actual agent implementations will be added as the project evolves based on the designs in [agent-ideas.md](agent-ideas.md).
