# Troubleshooting

Calm, practical steps. If nothing helps, note your **weballoon version** (Settings → App Updates) and **OS** when asking for support.

## Magic link does not link the device

- Confirm you clicked the link on the **same machine** where weballoon is installed.
- macOS / Windows: ensure **`weballoon://`** links open in weballoon (system “default handler” settings).
- Try **Resend Link** from **Settings → Account** after the cooldown.
- Check spam folders.

## “Free plan limit reached”

You have **10 apps** or are trying to create more than **2** workspaces on Free. Remove an app or workspace, or upgrade under **Plans** ([Plans & billing](plans-and-billing.md)).

## Site looks broken or blank

- **Reload** in the title bar.
- **Settings → Adblocker** — try turning blocking **off for that app only**.
- **Settings → Proxy** — confirm host, port, and bypass rules; save and let the app reload.

## No notifications from a site

- Enable **Run in background** for that app in **Settings → Notifications**.
- The site must actually use **web notifications**; some only use in-page toasts.
- If you are **inside** that app with it focused, weballoon may skip duplicating entries in the in-app bell (OS notifications may still appear depending on the site).

## Shortcut does not work

- Click outside website input fields (title bar or weballoon chrome), then try again ([Keyboard shortcuts](keyboard-shortcuts.md)).
- **Ctrl/Cmd+number** workspace jumps only register **inside** an open web app; from **My Apps** or **Settings** use the workspace button or **Shift+W** instead.

## High CPU or RAM

- **Settings → Task Manager** — sort by memory or CPU.
- Reduce **Run in background** apps.
- Close app views you are not using.

## Updates never appear

The **App Updates** card explains when automatic checks are **disabled** (development builds, some Linux setups, or environment flags). Install a **release** build from the official channel when possible.

## Closed window but weballoon still “there” (Windows / Linux)

A **tray icon** may be running. **Right‑click → Quit** to exit fully, or click the icon to show the window again ([Settings overview](settings.md)).

## Wrong theme after system change

weballoon’s theme is **manual** (Dark / Light) in Settings, not “follow system” in the current selector—pick the theme you want in **Appearance**.
