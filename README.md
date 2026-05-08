# job-tracker

A single-file job application tracker. No build step, no backend. Open `index.html`, your data lives in `localStorage`. Export to JSON whenever you want a backup.

I built this for myself while applying to remote engineering roles. Watching applications drift past 14 / 28 day thresholds was the actual missing piece — the tracker color-codes age so it's obvious which ones to follow up on.

## Features

- Add / edit / delete applications
- Status: draft, applied, interview, offer, rejected, ghosted
- Filter by status
- Stats: total, in-flight, interviewing, offers, closed-lost
- Age column auto-warns at 14d (yellow) and 28d (red)
- Export / import JSON (your only "backup")
- Dark mode by default
- Mobile responsive

## Run locally

```
open index.html
```

That's it. No npm, no install, no config.

## Stack

- One HTML file
- Vanilla JavaScript
- `localStorage` persistence
- No frameworks, no build, no dependencies
