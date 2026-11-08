# Pawchive Homebrew Tap

Homebrew cask for [Pawchive Client](https://github.com/tplw/Pawchive-Client),
a native client for the Pawchive archive.

## Install

```bash
brew tap tplw/pawchive
brew install --cask pawchive
```

Or install the cask directly:

```bash
brew install --cask tplw/pawchive/pawchive
```

## Update

```bash
brew upgrade --cask pawchive
```

## Notes

- Requires macOS 11 (Big Sur) or newer.
- The macOS build is unsigned. If Gatekeeper blocks it, right-click the app
  and choose **Open**, or allow it from **System Settings → Privacy & Security**.
- The cask downloads the universal DMG from the official GitHub release.
