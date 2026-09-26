# Horizon releases

Downloads for Horizon — a terminal-first workspace for running CLI agents.
This repository holds release files only.

## Arch Linux and Omarchy

```sh
yay -S horizon-desktop-bin
```

The AUR package `horizon-desktop-bin` downloads the archive from these
releases, checks its SHA-256, and installs the desktop app, the Host service
and the CLI, with a launcher entry. It depends on gtk4, libadwaita and vte4.

Each release lists every file's digest in `SHA256SUMS`.
