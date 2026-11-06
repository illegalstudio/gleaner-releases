# Gleaner

Gleaner is a desktop moodboard for macOS and Linux. Drag links, images and videos into the window or write notes by hand, give each one tags and a description, and browse them in a masonry grid with tag and text filters.

This repository only publishes the signed builds: download them from the [releases](https://github.com/illegalstudio/gleaner-releases/releases/latest).

## Install

**macOS** (Apple silicon and Intel, signed and notarized), with [Homebrew](https://brew.sh):

```sh
brew install --cask illegalstudio/tap/gleaner
```

**Arch Linux**, from the [Illegal Studio pacman repository](https://illegalstudio.github.io/pacman/). Add it once at the bottom of `/etc/pacman.conf`:

```ini
[illegalstudio]
SigLevel = Optional TrustAll
Server = https://illegalstudio.github.io/pacman/$arch
```

then install with `sudo pacman -Syu gleaner`.

**Other Linux distributions** (x86_64 and arm64): download the `.deb`, `.rpm` or `.AppImage` from the [latest release](https://github.com/illegalstudio/gleaner-releases/releases/latest). The AppImage carries its own GStreamer plugins; with the `.rpm`, install the GStreamer "good" and libav plugins to play videos.

`SHA256SUMS.txt` in every release lists the checksums of its files.
