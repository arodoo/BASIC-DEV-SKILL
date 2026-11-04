# BASIC-DEV-SKILL

A foundational, reusable set of base agent instructions, prompts, and documentation architecture standards for AI-assisted software development.

## Overview

This repository provides a standard set of development guidelines, architectural rules (DDD, SOLID, 120/80 limits), refactoring verifications, and documentation patterns following the Diátaxis framework.

## Structure

- `AGENTS.md` — Top-level entrypoint and guidance for AI agents working across projects.
- `agents/` — Instructions, prompts, and task templates:
  - `instructions/`: Global coding standards (`global.instructions.md`), refactoring rules (`refactor.instructions.md`), and testing policies (`test.instructions.md`).
  - `prompts/`: Standard prompts (`basic-instruction.prompt.md`, `validate-refactoring.prompt.md`).
  - `Todos/`: Project task trackers (`basic-todo.md`).
- `docs/` — Documentation organized according to Diátaxis principles (`explanation/`, `how-to/`, `reference/`, `tutorials/`).

## Usage

Clone or reference this repository as a base template or submodule whenever you initialize an AI-assisted development workspace.
