# Interactive-App-Workbook-v1

A reusable interaction pattern for complex applications: explain one decision, let the user act beside the instruction, verify real evidence, and correct the workflow when the result is empty.

## Canonical invocation

> 用 Interactive-App-Workbook-v1 設計這個 App

## Repository scope

This repository is a design and development guide—not a deployable investment system. It contains:

- UI/UX principles and layout blueprint.
- A Claude Code / Codex implementation prompt.
- A machine-readable question contract.
- Acceptance criteria for evidence, correction, accessibility, and responsive behavior.
- A sanitized GPS-ETF interaction demo as a reference implementation.

## Live pages

- Design whitepaper: `index.html`
- Sanitized GPS-ETF example: `gps-etf-demo.html`

The GPS-ETF page is a static, fictional UI/UX demonstration. It contains no brokerage account, statement image, real holding, credential, SQLite database, market-data API, backend, or order capability.

## Core contract

1. One question at a time.
2. Guidance on the left, the current action on the right.
3. Saving is not completion: read back evidence and verify it.
4. Empty results enter an editable Correct state instead of a dead end.
5. Every step states its owner, completion rule, result, and next action.

## GitHub Pages

Pushes to `main` deploy the `site/` directory through GitHub Actions.

