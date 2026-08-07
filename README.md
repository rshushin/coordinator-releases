# Maguf Coordinator — Downloads

Installers for the Coordinator desktop app (Maguf Engineering).
This repository contains **release binaries only** — the application source is private.

## Download the latest version

Go to **[Releases](https://github.com/rshushin/coordinator-releases/releases/latest)** and pick the file for your system:

| System | File |
|---|---|
| Windows | `Coordinator-Setup-<version>.exe` |
| macOS (Apple Silicon) | `Coordinator-<version>-arm64.dmg` |

No GitHub account is needed to download.

## Installing

**Windows** — run the `.exe`. Windows shows a warning because the app is not
code-signed: *More info → Run anyway*.

**macOS** — open the `.dmg`, drag **Coordinator** to Applications. On the first
launch, **right-click → Open → Open** (a plain double-click is refused for
unsigned apps).

**Before updating**, quit the running copy completely: the window's X only hides
it, and it keeps running in the menu bar / system tray. Right-click the Maguf
icon → יציאה.

After installing, the app version is shown at the bottom of the sidebar.

## Support

Report issues to the Maguf project maintainer. The sidebar's **יומן** button
opens the folder containing `app.log`, which is useful to attach.
