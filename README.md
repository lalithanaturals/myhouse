# My House — Household Accounts

A household accounts and home management app for a joint family:
ledger, bills and dues, chits and loans, payroll, family transfers,
procurement, housekeeping schedule, meal plan, tasks, maintenance,
reminders, reports, and a Liquid Glass design.

## Two ways it runs

| | Claude version | This GitHub version |
|---|---|---|
| Where data is saved | Secure shared database | This browser, this device only |
| Logins and roles | Admins (owner and Editors) and family (Contributors) | None |
| Family entry and approvals | Yes | No |

The GitHub copy is the same code. When it opens outside Claude it
cannot reach Claude's database, so it switches to device-only mode and
starts with empty books.

## Files

- `index.html` — the whole app (HTML, CSS and JavaScript in one file).

## Editing with GitHub Copilot

Open the folder in VS Code and ask Copilot about `index.html`.
The app's logic sits in the `<script id="appjs">` block at the end of the file.
