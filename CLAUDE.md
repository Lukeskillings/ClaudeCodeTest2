# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A browser-based Tic Tac Toe game. The entire application is a single self-contained HTML file (`tictactoe.html`) with inline CSS and JavaScript — no build tools, dependencies, or server required.

## Running

Open `tictactoe.html` directly in a browser:
```
open tictactoe.html
```

## Architecture

- **Single-file app**: All markup, styles, and game logic live in `tictactoe.html`
- **Game state**: Managed by module-level variables (`cells` array, `currentPlayer`, `gameOver`) reset via `init()`
- **Win detection**: Checked against a static list of winning index combinations (`winCombos`)

## Workflow

- **Commit and push regularly**: After completing any meaningful change, commit with a clean, descriptive message and push to GitHub (`origin/main`). This ensures work is never lost and we can revert easily if needed.
- **Commit granularity**: Prefer small, focused commits over large ones. Each commit should represent a single logical change.
