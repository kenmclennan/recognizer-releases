# Recognizer releases

Recognizer is a native Mac viewer for a codebase's modules and dependencies: point it at a repository and it scans it, then lets you explore its folders, files and the edges between them, starting from what you pick. This repository holds the built apps and the update manifest; the source is private.

## Install

1. Open the [latest release](https://github.com/kenmclennan/recognizer-releases/releases/latest) and download `Recognizer.app.tar.gz` (Apple silicon only).
2. Unpack it and move `Recognizer.app` to `~/Applications`.
3. The app is ad-hoc signed, not Apple-signed, so macOS blocks the first open. Open it once, then go to System Settings > Privacy & Security and choose Open Anyway. Alternatively run `xattr -dr com.apple.quarantine ~/Applications/Recognizer.app` before the first open.

## Updates

Later updates install from inside the app. When a newer release exists, the footer offers to install it; choosing it downloads the release, installs it and relaunches.
