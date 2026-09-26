# Horizon releases

Downloads for Horizon — a terminal-first workspace for running CLI agents.
This repository holds release files only.

## Arch Linux and Omarchy

```sh
curl -fLO https://github.com/harshach/horizon-releases/releases/download/v0.7.3/horizon-desktop-bin-0.7.3-1-$(uname -m).pkg.tar.zst
sudo pacman -U horizon-desktop-bin-0.7.3-1-$(uname -m).pkg.tar.zst
```

The package installs the desktop app, the Host service and the CLI, with a
launcher entry, and pulls in gtk4, libadwaita and vte4. To upgrade, run the
same two lines with the next release's version. (The package is downloaded
first because pacman asks a URL for a signature file, and these packages are
not signed.)

Each release lists every file's digest in `SHA256SUMS`. An AUR package,
`horizon-desktop-bin`, follows once the AUR reopens registration.
