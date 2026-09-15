# prioritization-boards

Single-file HTML/CSS/JS tool (`index.html`) — MoSCoW prioritization + Make It
Work / Right / Fast execution tracker, with multi-board support. No build
step, no dependencies beyond the Google Fonts link.

Deployed via GitHub Pages from `main` / root:
https://kongwsnwork.github.io/prioritization-boards/

## Workflow

- **Push to `origin/main` after every change that gets committed** — the
  user wants this repo kept in sync with GitHub continuously, not batched.
  Commit with a normal descriptive message, then push in the same turn
  unless the user says otherwise.
- No CI/build — pushing to `main` is what ships the change (Pages serves
  straight from the branch).
