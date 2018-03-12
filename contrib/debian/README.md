
Debian
====================
This directory contains files used to package pyrod/pyro-qt
for Debian-based Linux systems. If you compile pyrod/pyro-qt yourself, there are some useful files here.

## pyro: URI support ##


pyro-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pyro-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pyro-qt binary to `/usr/bin`
and the `../../share/pixmaps/pyro128.png` to `/usr/share/pixmaps`

pyro-qt.protocol (KDE)

