# Diyar — releases

Release builds of **Diyar**, a private macOS app for the admin and money side of a small UK
psychotherapy practice. This repository holds only the built app (no source code). All practice
data stays on the Mac where Diyar runs.

## First install

1. Download `Diyar-<version>-universal-mac.zip` from the [latest release](../../releases/latest).
2. Unzip it and drag **Diyar** into **Applications**.
3. Open it. Diyar isn't signed by Apple, so the first time macOS may say it can't be opened: go to
   **System Settings → Privacy & Security** and click **Open Anyway**.

## Updates

From version 1.0.13, Diyar checks here shortly after it opens and shows a small banner when a newer
version exists. **Settings → App updates** downloads and installs it. Every update is signed, and
Diyar installs only signed versions newer than the one it is running. Diyar copies its database
before running a new version.

Each release has two files: the app ZIP and `diyar-update.json` (the signed update information the
app reads). You can always install a version by hand from its release page instead.
