# Astrolabe Homebrew tap

```bash
brew install mercurian-labs/tap/astrolabe          # the astrolabe command (also installed as alab)
brew install --cask mercurian-labs/tap/astrolabe   # the desktop app
```

Update the command with `brew upgrade astrolabe`. The desktop app updates itself.

The formula installs the self-contained CLI from each stable
[Astrolabe release](https://github.com/mercurian-labs/astrolabe/releases): macOS on Apple silicon,
and Linux on x64 and arm64. The cask installs the desktop app on Apple silicon and Intel Macs.

The release workflow in [mercurian-labs/astrolabe](https://github.com/mercurian-labs/astrolabe)
writes both files (`packaging/homebrew/render.sh`), so change them there rather than here.
