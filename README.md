# Tsuba

Git client for macOS. This repository only hosts the downloads.

## Download

[Download the latest version](https://github.com/breight-code/tsuba-releases/releases/latest/download/Tsuba.zip). Requires macOS 14 or later, Apple Silicon or Intel.

## First launch

Tsuba is not signed with an Apple Developer ID, so macOS blocks the first launch.

1. Unzip and move `Tsuba.app` to `Applications`.
2. Open it once, then go to System Settings > Privacy & Security and click "Open Anyway".

Or from Terminal:

```sh
xattr -dr com.apple.quarantine /Applications/Tsuba.app
```

## Updates

Tsuba checks this repository once a day and tells you when a new version is out. You can also use Tsuba > Check for Updates.
