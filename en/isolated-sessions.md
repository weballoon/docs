# Isolated sessions

Each weballoon app runs in its **own browser-style session**. Sessions do **not** share:

- Cookies  
- Local storage and similar site data  
- Logged-in state (unless you sign in separately in each app)

So two apps for the same service (or two Gmail installs) behave like **two separate profiles**, as long as they are separate app entries.

## Why it matters

- **Work / personal:** Same service, different accounts, no constant logging in and out in one tab strip.
- **Security:** A risky site you sandbox in its own app does not read cookies from your bank app.
- **Predictability:** Clearing data for one app (in **Settings → Privacy & Data**) targets **that** app only.

## “Default view” is not weaker isolation

Default vs named workspace is only **organization**. Isolation is **per app**, not per workspace name.

## Related settings

- **Privacy & Data** — Clear one app or all apps; optional auto-clear when quitting; Do Not Track; diagnostics opt-in; open your local data folder.
- **Permissions** — Camera, microphone, screen sharing, and location are **blocked by default** until you allow them per app.

See [Privacy & local data](privacy-and-local-data.md) and [Permissions](permissions.md).
