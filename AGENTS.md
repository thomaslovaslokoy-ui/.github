# AGENTS.md

This file provides guidance for AI coding agents working on this repository.

## Repository Overview

This repository contains shared community files for [the Vercel organization](https://vercel.com/). It is intentionally minimal and serves as a central location for org-wide community health files such as security policies.

## Repository Structure

```
.
├── README.md       # Brief description of the repository
├── SECURITY.md     # Security vulnerability reporting policy
└── AGENTS.md       # This file — guidance for AI agents
```

## Guidelines for AI Agents

### Scope of Changes

- This repository contains **community health files** only. Do not add application code, build tooling, or unrelated documentation.
- Any new files should be community-facing documents (e.g., `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SUPPORT.md`).

### Editing Existing Files

- `SECURITY.md`: Changes must preserve the contact address (`responsible.disclosure@vercel.com`) and the core reporting instructions. Do not remove or alter security-critical content.
- `README.md`: Keep it concise. It should remain a short description pointing to the Vercel organization.

### Commit Conventions

- Use clear, descriptive commit messages (e.g., `Add CODE_OF_CONDUCT.md`, `Update SECURITY.md contact info`).
- Prefer small, focused commits over large batched changes.

### No Build or Test Steps

This repository has no build system, test suite, or CI pipeline. There is nothing to install or run.

### Pull Requests

- Open PRs against the `main` branch.
- PR descriptions should briefly explain what community file is being added or updated and why.
