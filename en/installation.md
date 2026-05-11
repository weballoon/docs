# Installation & supported platforms

Official desktop builds target **macOS**, **Windows**, and **Linux**, for **64-bit Intel (x64)** and **Apple Silicon / ARM64** where applicable.

## macOS

Installers are built as **DMG** and **ZIP** (both architectures in release builds). After opening the DMG, drag **weballoon** into Applications (or use your usual workflow).

**Deep link:** The app registers the `weballoon://` scheme so email **magic links** can return to the app when you click them.

## Windows

The release format is **NSIS** (installer) for x64 and arm64.

Same **`weballoon://`** scheme applies for magic-link completion.

## Linux

Release builds use **AppImage** (x64 and arm64). Automatic in-app updates on Linux may only work when you installed from a supported release package (the app explains if updates are unavailable in your environment).

## Updates

In **Settings**, under the account area, the **App Updates** card lets you **check for updates** and, when a download is ready, **restart to update**. If an update is downloaded in the background, weballoon may prompt you to restart when it is convenient.

Some environments (for example local development builds) do not offer automatic updates; the card will say updates are unavailable and why.

## System requirements

weballoon is a desktop web runtime. For smooth use, a normal modern computer with a few gigabytes of free RAM is enough; each open or background app uses additional memory (see [Hibernation & memory](hibernation-and-memory.md)).
