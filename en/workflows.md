# Workflows & tips

Real patterns that fit weballoon’s **isolated apps** and **workspaces** model.

## Work vs personal

1. Create workspaces **Work** and **Personal**.
2. Add each site as its **own app** so sessions never mix.
3. Use **Shift+W** to flip contexts quickly.

## Multi-account on one service

Add **two apps** with different names (for example “Gmail — work” and “Gmail — home”) pointing at the same host. Each keeps its own cookies. You cannot duplicate the **same URL in one workspace**; put the second copy in another workspace or use distinct entry URLs if the service offers them.

## Research and focus

- Put distracting social apps in a **separate workspace** from documentation tools.
- Turn **Run in background** off for heavy sites you only read occasionally ([Notifications](notifications.md)).

## Calls and meetings

Enable **Camera** and **Microphone** only for the video app you trust ([Permissions](permissions.md)). If the site still fails, check whether **Adblocker** breaks the page and disable it for that app only ([Adblocker](adblocker.md)).

## Proxy-heavy use (including SEO or regional checks)

weballoon does **not** include a built-in SEO suite. It **does** support **per-app HTTP/HTTPS/SOCKS proxies** ([Proxy](proxy.md)). A practical setup:

- One workspace for **domestic** tools (no proxy).
- Another workspace or app entries for **geo-specific** checks routed through a proxy you already have from a legitimate provider.

Always respect your provider’s terms and applicable laws.

## Shared computer

- Use **PIN protection** on personal apps ([PIN protection](pin-protection.md)).
- Consider **Auto-clear on Exit** under Privacy ([Privacy & local data](privacy-and-local-data.md)).

## Low-memory machines

- Limit **Run in background** apps.
- Keep fewer large apps “open” at once; rely on the grid and accept occasional reloads ([Hibernation & memory](hibernation-and-memory.md)).
