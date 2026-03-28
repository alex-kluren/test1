# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with this repository.

## Project Overview

This is the `test1` repository. Update this file as the project grows to keep Claude informed of important conventions, architecture decisions, and workflows.

## Repository Structure

```
test1/
├── .github/
│   └── copilot-instructions.md   # GitHub Copilot custom instructions
├── CLAUDE.md                      # This file – Claude Code instructions
└── README.md                      # Project README
```

## Development Guidelines

- Make the smallest change necessary to address a task.
- Follow existing code style and conventions in the repository.
- Avoid introducing unnecessary dependencies.
- Write clear, self-explanatory code; add comments only where intent is non-obvious.
- Always validate that changes don't break existing behavior.

## Key Commands

Document build, test, and lint commands here once the project has them. For example:

```bash
# Install dependencies
# npm install

# Run tests
# npm test

# Lint
# npm run lint
```

## AI Agent Setup

This repository is configured for efficient AI-assisted development:

- **GitHub Copilot**: Custom instructions are in `.github/copilot-instructions.md`.
- **Claude Code**: Project instructions are in this file (`CLAUDE.md`).
