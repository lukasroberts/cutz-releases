# Cutz — Releases

Public distribution point for [Cutz](https://cutz-bef64.web.app), a desktop app
for learning and practising DJ scratching.

There is no source code here. Cutz is developed in a private repository; this
repo exists purely so the app's built-in updater can fetch builds, which it
can't do from a private repo's release assets.

## Downloads

Grab the latest `.dmg` from [Releases](../../releases/latest).

**Requirements:** macOS on Apple Silicon (M1 or newer). Intel Macs aren't
currently supported.

## Automatic updates

Installed copies check [`latest.json`](../../releases/latest/download/latest.json)
on launch and prompt when a newer version is available. Every update bundle is
signed; the app verifies that signature before installing anything.

## Contents of a release

| File | What it is |
|---|---|
| `Cutz_<version>_aarch64.dmg` | The installer. Signed, notarised and stapled — Gatekeeper opens it without warnings. |
| `Cutz.app.tar.gz` | The bundle the updater downloads in-place. |
| `Cutz.app.tar.gz.sig` | Updater signature for the above. |
| `latest.json` | Update manifest the app polls. |

Releases are built and published by GitHub Actions from the private repo.