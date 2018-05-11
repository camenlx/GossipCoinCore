
Debian
====================
This directory contains files used to package gossipcoind/gossipcoin-qt
for Debian-based Linux systems. If you compile gossipcoind/gossipcoin-qt yourself, there are some useful files here.

## gossipcoin: URI support ##


gossipcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gossipcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gossipcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/gossipcoin128.png` to `/usr/share/pixmaps`

gossipcoin-qt.protocol (KDE)

