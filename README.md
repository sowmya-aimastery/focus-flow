# Focus Flow

A simple, single-file Pomodoro-style focus timer with lightweight task tracking. Everything runs in the browser — no build step, no backend, no dependencies.

## Features

- **Focus / Short Break / Long Break timer** with a 25 / 5 / 15 minute default cycle. Every 4th focus session rolls into a long break automatically.
- **Task list** — add tasks, click one to make it the active task, and completed focus sessions tally up against it.
- **Daily session streak** shown in the header, reset automatically each day.
- **Sound + confetti** celebration when a focus session finishes.
- **Light/dark theme** follows your OS setting automatically.
- **Local-only storage** — tasks and streak data are saved with `localStorage`, so nothing leaves your device.

## Usage

Open `index.html` in any modern browser. That's it — no install, no server required.

```
open index.html
```

## Project structure

The entire app (markup, styles, and script) lives in a single `index.html` file for simplicity.
