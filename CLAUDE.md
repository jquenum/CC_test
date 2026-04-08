# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

CC_test is a collection of standalone browser games built as single HTML files with inline CSS and JavaScript. No build tools, frameworks, or dependencies — just open the files in a browser.

## Architecture

Each game is a self-contained `.html` file with embedded `<style>` and `<script>` tags:

- **shooter.html** — Canvas-based retro shooter game using a game loop (`requestAnimationFrame`), sprite rendering, wave-based enemy spawning, and collision detection. Configuration lives in the `CFG` object at the top of the script.
- **tictactoe.html** — DOM-based tic-tac-toe with minimax AI (alpha-beta pruning). Uses a 1D array for board state.

## Development

No build step. Open any `.html` file directly in a browser to run it. Edit and refresh.

## Git

- Remote: `origin` → `github.com:jquenum/CC_test` (personal GitHub)
- Local git email is set to personal (`jerome.quenum.research@gmail.com`), overriding the global work config
- Commit and push changes after making modifications to maintain history
