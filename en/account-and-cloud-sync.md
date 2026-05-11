# Account linking & cloud sync

## Account linking (magic link)

Linking ties this **device** to an **email** on weballoon’s service so billing and optional sync can work.

1. Open **Settings → Account** (or complete onboarding).
2. Enter **Email Address** and an optional **Device Label** (for your own reference, for example `desktop-mac`).
3. Click **Send Magic Link**.
4. Check email and **click the link**. weballoon completes linking automatically when the link opens the app (via the `weballoon://` handler).

While waiting, you can **Resend Link** (with a short cooldown). You can **Disconnect Device** when connected.

If you prefer not to link, you can skip during onboarding and use weballoon **locally**; you can link later from Settings.

## Cloud sync

Under **Settings → Account**, the **Cloud Sync** section explains:

- Sync saves your **apps and workspaces** to the cloud **without** your browsing data or site logins (wording in the app: no browsing data or logins in the snapshot).
- You can turn **Cloud Sync** on or off.
- **Sync on Exit** runs one more sync of the device data when weballoon closes (when enabled).

You also have **Pull from Cloud** and **Push to Cloud** for a manual refresh. The panel shows namespace, version, last push, and last pull timestamps when available.

Sync requires a **connected** account. Errors appear in the same panel if something fails.

## Billing and account

**Plans** and subscription management are tied to a linked account where checkout is available. See [Plans & billing](plans-and-billing.md).

## Privacy note

The app states that **proxy passwords** are encrypted on the device and **not** synced to the cloud. Per-app proxy details are covered in [Proxy configuration](proxy.md).
