# Notifications

weballoon handles two related ideas: **OS-level notifications** from sites that use the browser notification API, and an **in-app notification list** so you can catch up without hunting for toasts.

## In-app notification center

- Click the **bell** on the dock, or press **Shift+N** (when focus allows; see [Keyboard shortcuts](keyboard-shortcuts.md)).
- You can **mark all read**, open an item to jump to the app, or dismiss entries.
- While you are **already viewing** an app, new notifications from that same app are **not duplicated** in the in-app list (the app may still use the OS notification where the site supports it).

Notifications are kept in a short list (up to 100 recent items) so the panel stays useful.

## “Run in background” (per app)

In **Settings → Notifications**, each app has a toggle labeled **Run in background** in English UI copy. When enabled:

- That app’s session can stay active so things like **websockets** keep working when you are looking at another app or another workspace.
- weballoon shows a reminder that **each** background app uses roughly **50–150 MB** of memory (approximate; real use varies by site).

If you add no apps yet, the panel explains you should add apps first, then choose which should stay running.

## Practical use

- Turn **Run in background** on for chat or mail apps where you want alerts while working elsewhere in weballoon.
- Leave it off for heavy or rarely used sites to save RAM.

See also [Hibernation & memory](hibernation-and-memory.md).
