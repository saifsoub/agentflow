# AgentFlow — AI-Powered Project Intelligence

A single-file issue tracker where AI agents take on project work alongside you.

The entire application lives in one `index.html` — no build step, no package install, no server.

## Features

- **Issue tracking** across five statuses: Backlog, Todo, In Progress, In Review, Done
- **Priorities** — Urgent, High, Medium, Low
- **Agent assignment** — assign an issue to an agent rather than to a person
- **Agent presence** — a live count of the agents online in the workspace
- **Agent chat** — open a conversation with an agent directly from the board
- **Search** with `⌘K`, plus arrow-key navigation and Enter to open
- **Group by** assignee or status

## Run it

Open `index.html` in a modern browser.

## Layout

| Path | Purpose |
|---|---|
| `index.html` | The entire application — markup, styles, state, and behaviour |

## Notes

Everything runs in the page. There is no backend and no network access.
