# Weekly Planner — demo

A single-page personal planner: weekly grid, time blocks, overlaid calendars, to-do list, templates, clash detection. Self-contained HTML, no build step, no backend.

**Live demo:** after deployment, `https://YOUR-USERNAME.github.io/timetable-demo/`.

## Features shown

- 5-week view with time blocks per day (morning routine, working time, lunch, family time, evening).
- Two overlaid calendars (personal + partner) with distinct colours and icons.
- Tasks live on the grid with category, optional time-within-block, and a "needs partner" flag.
- Clash warnings when a task's time overlaps a calendar event or another task.
- Overflow warnings + "ghost" echoes when a task extends beyond its block.
- Quick-add templates you can click-then-drop on any block.
- To-do list tab for capture-first-schedule-later.
- Export / Import JSON for portable state between devices.

## Data

All events and names in this demo are placeholder examples. The production version binds to live Google Calendars via a Flask backend; this public copy has hardcoded sample data and no backend, so state is browser-session only (export/import to persist).

## Tech

Single HTML file (~75 KB). No external dependencies. Runs wherever a modern browser opens it.
