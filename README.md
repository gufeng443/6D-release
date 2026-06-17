# 6D Release

This public repository is only for 6D desktop release downloads, the update
manifest, and the static download page.

It must never contain:

- product source code
- license server code
- admin UI code
- secrets, tokens, `.env`, `.dev.vars`
- account data, exported packages, logs, or test data

Download page:

- https://gufeng443.github.io/6D-release/

Release assets are uploaded through GitHub Releases. The root `latest.json`
points clients to the newest approved build after the package has passed QA.
