# weballoon documentation

End-user documentation for **[weballoon](https://weballoon.app)** — the desktop workspace for web apps (isolated sessions, workspaces, optional cloud sync for your setup).

This repository contains **Markdown only**. It is meant to ship beside help centers, websites, or in-app links. It does **not** include the application source code.

---

## Languages

| Folder | Status |
|--------|--------|
| [`en/`](en/README.md) | **Canonical** — complete user guide (start here if unsure). |
| [`es/`](es/README.md) | Spanish — same file set as `en/`. |
| [`pt/`](pt/README.md) | Portuguese — same file set as `en/`. |
| [`fr/`](fr/README.md) | French — same file set as `en/`. |
| [`de/`](de/README.md) | German — same file set as `en/`. |
| [`ru/`](ru/README.md) | Russian — same file set as `en/`. |
| [`it/`](it/README.md) | Italian — same file set as `en/`. |

Filenames are identical across languages (e.g. `keyboard-shortcuts.md`) so links and tooling can switch locale by path prefix only.

---

## Browse the docs

Open the README for your language — each has a full table of contents and quick facts:

**[English → `en/README.md`](en/README.md)**

Topics include: getting started, installation, applications, workspaces, account & cloud sync, notifications, privacy, permissions, proxy, adblocker, PIN protection, keyboard shortcuts, picture-in-picture, settings, plans, troubleshooting, and FAQ.

---

## Principles (for contributors)

- **Audience:** normal users, not developers. No internal architecture, private APIs, or implementation secrets.
- **Accuracy:** describe what the shipped app actually does; verify against the desktop product when in doubt.
- **No invention:** do not document features, shortcuts, or menus that do not exist.
- **App source:** the weballoon app lives outside this repo; read-only inspection is fine, **do not** commit changes to the app from here.

---

## Repository layout

```
git-docs/
├── README.md          ← you are here
├── en/                ← English (22 topic files + README)
├── es/                ← Spanish
├── pt/                ← Portuguese
├── fr/                ← French
├── de/                ← German
├── ru/                ← Russian
└── it/                ← Italian
```

Each locale folder contains the same Markdown filenames (no nested `docs/` layer).

---

## License / ownership

Documentation text is maintained for the weballoon project. If you add a license file or contribution guidelines later, link them from this README.
