# Cutz — Releases

Public distribution point for [Cutz](https://cutz-bef64.web.app), a desktop app
for learning and practising DJ scratching.

## Downloads

Grab the latest `.dmg` from [Releases](../../releases/latest).

**Requirements:** macOS on Apple Silicon (M1 or newer). Intel Macs aren't
currently supported.

## Automatic updates

Installed copies check for the latest update on launch and prompt when a newer version is available.

## Contents of a release

| File | What it is |
|---|---|
| `Cutz_<version>_aarch64.dmg` | The installer. Signed, notarised and stapled — Gatekeeper opens it without warnings. |
| `Cutz.app.tar.gz` | The bundle the updater downloads in-place. |
| `Cutz.app.tar.gz.sig` | Updater signature for the above. |
| `latest.json` | Update manifest the app polls. |
