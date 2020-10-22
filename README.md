# Post Arch-Based Install

## Installation:

Pre-requisites: **(1)** System with an Arch-based Linux distribution, **(2)** network connection.

	1. Clone with `git clone https://github.com/majamin/LARBS.git` and `cd LARBS`
	2. Look over `larbs.sh` and make it executable: `chmod +x larbs.sh`
	3. Run `larbs.sh` as root

## What is this?

This repo is a fork of Luke Smith's [LARBS](https://github.com/LukeSmithxyz/LARBS.git).
It installs a basic and no-bloat environment on a fresh Arch install.

## Customization

Programs installed can be changed in `progs.csv`.
An `A`, `G`, or `P` in the first column indicates `yay`, `git`, and `pip` installs, respectively.
Otherwise, programs are installed with `pacman`.

Please see Luke's LARBS for other customizations.

## Screenshot

![screenshot](https://raw.githubusercontent.com/majamin/LARBS/master/screenshot.png)
