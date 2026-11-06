# pom

A pomodoro timer with a flexible finish.

Live: https://edwardandress.github.io/pom/

## The orange phase

Most pomodoro timers snap: the bell rings, you stop. This one gives you a window.

- **Green** — you're inside the work session.
- **Orange** — the session is "done", but you can keep going for a configurable flex period to finish the thought, land the test, close the paragraph.
- **Red** — flex is up; a break is overdue.

Breaks still happen. You just don't have to break mid-sentence to get one.

## Tech

One file: `index.html`. Vanilla JS, no build step, no dependencies. State (settings, current phase, cycle count, the note you left for your future self) lives in `localStorage`, so it survives refreshes and tab closes. Deployed via GitHub Pages straight from `main`.

To hack on it, open `index.html` in a browser. That's it.

## Contributions

Issues and PRs welcome. If you've got an idea for a different finish behaviour, a sound, a keyboard shortcut, or anything else — open an issue first so we can talk shape, then send a PR.
