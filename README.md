# TLE-App Desktop Distribution

Public distribution point for the TLE-App desktop installers and Tauri updater
manifests. Application source lives in the private `simoPh83/TLE-App` repository.

## Channels

Each channel has its own updater manifest served via GitHub Pages:

| Channel | Manifest URL | Purpose |
| --- | --- | --- |
| dev | `https://simoph83.github.io/TLE-App-Desktop/dev/latest.json` | Developer installs and update-path testing |
| staging | `https://simoph83.github.io/TLE-App-Desktop/staging/latest.json` | Release candidates for user feedback |
| stable | `https://simoph83.github.io/TLE-App-Desktop/stable/latest.json` | Production releases |
| canary | `https://simoph83.github.io/TLE-App-Desktop/canary/latest.json` | Developer-only pre-publication verification of production-signed updates |

Signed installers are published as assets on GitHub Releases in this repository.

Nothing secret belongs here: this repository is public. Do not commit
credentials, private data or sensitive release notes.
