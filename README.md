# kkmg — Mizan Launcher updates

This repository hosts the automatic updates for **Mizan Launcher** (لانشر ميزان) and its apps.

- `updates/launcher/` — the launcher itself (`manifest.json` + package zip)
- `updates/mizan/` — Mizan Trading app

The launcher reads `https://raw.githubusercontent.com/kkmg80/kkmg/main/updates/<app>/manifest.json`,
verifies the SHA-256 of the package, backs up, installs and restarts automatically.
