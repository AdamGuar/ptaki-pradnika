# AGENTS.md

## Project Context
- This is a fully static HTML presentation project (no build pipeline).
- Main entry point: `index.html`.
- Assets (photos/audio) are served directly from the repository structure.

## Local Run
- Start a static server from repo root:
  - `python -m http.server 8765 --directory D:/workspace/prezentacja`
- Open:
  - `http://localhost:8765`

## Editing Notes
- Keep the project static (no framework/tooling migration unless explicitly requested).
- Prefer minimal, targeted changes to `index.html` and related static assets.
- Preserve keyboard/touch navigation behavior and audio playback.

## Validation
- After changes, verify:
  - Pages/slides still navigate with keyboard.
  - Images load correctly.
  - Bird audio buttons still play sounds.
