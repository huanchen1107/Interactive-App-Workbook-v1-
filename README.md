# Interactive-App-Workbook-v1

A reusable interaction pattern for complex applications: explain one decision, let the user act beside the instruction, verify real evidence, and correct the workflow when the result is empty.

## Canonical invocation

> 用 Interactive-App-Workbook-v1 設計這個 App

## Live examples

- Design whitepaper: `index.html`
- Sanitized GPS-ETF example: `gps-etf-demo.html`

The GPS-ETF page is a static, fictional demonstration. It contains no brokerage account, statement image, real holding, credential, SQLite database, or order capability.

## Core contract

1. One question at a time.
2. Guidance on the left, the current action on the right.
3. Saving is not completion: read back evidence and verify it.
4. Empty results enter an editable Correct state instead of a dead end.
5. Every step states its owner, completion rule, result, and next action.

## GitHub Pages

Pushes to `main` deploy the `site/` directory through GitHub Actions.

