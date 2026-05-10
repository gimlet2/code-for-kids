# code-for-kids

A tiny browser-based playground to teach programming with Python.

## Features

- Visual game field with a controllable actor.
- Python action library in browser (`move_forward`, `turn`, `collect`).
- Multiple tasks with concrete goals:
  - Collect all stars.
  - Navigate a maze and collect the treasure.
- Task progress tracking.
- Per-task code persistence in `localStorage`.

## Run locally

Open `index.html` in a browser, or serve the folder with a static server:

```bash
python -m http.server 8000
```

Then visit: `http://localhost:8000`
