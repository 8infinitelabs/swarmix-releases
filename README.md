# Swarmix releases

Public release artifacts + auto-update manifest (`latest.json`) for the Swarmix
desktop app. The source lives in a private repo; this repo only holds the
built, signed installers that the in-app auto-updater downloads.

Releases are built by `.github/workflows/release.yml` (manual dispatch with the
private-repo tag to build).
