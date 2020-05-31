---
title: Linux
nav_order: 2
layout: page
description: ""
parent: Download
---
# Download for Linux

## Flatpak
Can be installed on any Linux distribution. Find Vorta on [Flathub](https://flathub.org/apps/details/com.borgbase.Vorta). To install:
```
$ flatpak install flathub com.borgbase.Vorta
```

Settings can be transferred by copying `~/.local/share/Vorta/settings.db` to `~/.var/app/com.borgbase.Vorta/data/Vorta/`.

## Install from Source
The most generic way is to install it as Python package using [PIP](https://pip.readthedocs.io/en/stable/installing/). First [install](https://borgbackup.readthedocs.io/en/stable/installation.html) Borg using the package of your distribution or via PyPI. The latter needs some additional [source packages](https://borgbackup.readthedocs.io/en/stable/installation.html#dependencies). Then install Vorta from PyPI. Your local Python version should be >= 3.6.
```
$ pip3 install --upgrade setuptools pip
$ pip3 install vorta
```

## Distribution Packages

### Arch Linux
Use the [AUR package](https://aur.archlinux.org/packages/vorta/) maintained by [@bjo81](https://github.com/bjo81).
```
$ yaourt -S vorta
```

**Looking to maintain a package?** [Open](https://github.com/borgbase/vorta/issues/new) an issue or pull request and it will be added here.
