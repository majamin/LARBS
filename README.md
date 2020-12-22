## What is this?

This repo is basically a fork of Luke Smith's [LARBS](https://github.com/LukeSmithxyz/LARBS.git).
It installs [dwm](https://dwm.suckless.org/) along with some basic software.
It requires an Arch-based install.

## Screenshot

![screenshot](https://raw.githubusercontent.com/majamin/LARBS/master/screenshot.png)

## Installation:

**Pre-requisite**: A minimal [Arch-based Linux install]() with networking.
Although it's best to start with a minimal Arch install, as long as
you have an Arch-based distro, you can can run the `larbs.sh` script.

1. You just rebooted after a minimal Arch install.
2. As root, clone with `git clone https://github.com/majamin/LARBS.git`.
3. `cd LARBS`, look over `larbs.sh` and make it executable: `chmod +x larbs.sh`.
4. Run `larbs.sh`, and reboot.

## tldr; larbs.sh

The script creates a wheel user and installs all of the programs
in `progs.csv`. Unlabelled programs use pacman, `yay` for **A** (AUR),
`pip` for **P**, and `git clone` and `make` for **G**.

## Display manager

It's possible to set this up, but this script does not do it for you.
See https://github.com/nbirnel/dwm-from-gdm as an example of how to do this.

## Post-install

1. Generate a GPG key pair or import yours.
2. Use `pass init YOUR@EMAIL.COM` and `pass add local/USERNAME@\`hostname\``
3. Add `auth optional pam_gnupg.so`
