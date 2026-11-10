# Yetly Auto Job Adder — Update Feed

This public repository hosts released builds for the **Yetly Auto Job Adder** Windows desktop app. It contains **no source code and no user data**.

The app checks `releases/latest` when it opens. Each release provides:

- `YetlyAutoJobAdder-Windows.zip` — the packaged application
- `latest.json` — version, zip name and SHA-256 checksum

The app only installs a download whose SHA-256 matches `latest.json`. Accounts, settings and job history stay in `%LOCALAPPDATA%\YetlyAutoJobAdder` and are never part of an update.

Maintained by the app owner. Do not upload builds here by hand; publish with `gh release create`.
