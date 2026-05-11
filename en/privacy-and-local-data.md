# Privacy & local data

Open **Settings → Privacy & Data**.

## What stays local

The app emphasizes that your **data stays on your computer**. The settings screen shows:

- Approximate **storage** used under the user data area.
- Counts of **apps** and **workspaces**.
- A path to the main local database file (shown as `weballoon.json` under your user data folder).
- **Open Folder** — opens that user data directory in the system file manager.

## Clearing data

- **Clear data** (per app) — Removes that app’s cookies, cache, and stored site data from its isolated session. The app may reload the next time you open it.
- **Clear All Data** — Removes cookies, cache, and storage **for all apps**. This is destructive; weballoon asks you to confirm.

## Automatic cleanup (on quit)

Two toggles persist across restarts:

1. **Auto-clear on Exit** — When you quit weballoon, browsing data for apps is cleared (cookies, cache, and the storage types the app clears on exit).
2. **Auto-clear Cache** — Despite older wording elsewhere about “periodically,” the implementation clears **cache when weballoon exits** (not on a timer during the day). If both auto options are on, the stronger “clear browsing data on exit” path runs.

Use these if you want a fresh slate after each session.

## Do Not Track

**Send Do-Not-Track Header** asks sites to respect DNT. Not all sites honor it; this is a request, not a guarantee.

## Crash and error reports

**Share crash & error reports** is **off by default**. If you turn it on, the app describes sending **sanitized technical diagnostics** to improve stability, **not** your browsing content, credentials, or history.

## App isolation (reminder)

Each app has **isolated storage**. Clearing or auto-clearing affects **that partition**, not your other apps.

See [Isolated sessions](isolated-sessions.md).
