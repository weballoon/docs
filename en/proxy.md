# Proxy configuration

Open **Settings → Proxy**.

## Per-application routing

Each app can be routed through its **own** proxy, or **none**. This is useful for:

- Corporate HTTP proxies for work apps only.
- SOCKS access for specific tools.
- Regional testing when combined with isolated sessions.

## Fields (when a proxy is enabled)

- **Protocol** — HTTP, HTTPS, SOCKS4, or SOCKS5.
- **Host** and **Port**.
- **Username** (optional).
- **Password** (optional). The UI explains that a saved password can be left blank to keep the previous one, and there is an action to **clear saved password**.
- **Bypass rules** — Comma-style list (placeholder example in app: `localhost, 127.0.0.1, *.internal`).

## Saving

**Save & Reload** stores settings and **reloads that application** so new connections use the route. The app warns that proxy changes **close existing connections** for the affected app.

## Security note

The **Account** area states that proxy **passwords are encrypted on this device** and are **not synced to the cloud**.

## If the list is empty

Add at least one application first; the proxy screen explains that.
