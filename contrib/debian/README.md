
Debian
====================
This directory contains files used to package scud/scu-qt
for Debian-based Linux systems. If you compile scud/scu-qt yourself, there are some useful files here.

## scu: URI support ##


scu-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install scu-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your facqt binary to `/usr/bin`
and the `../../share/pixmaps/fac128.png` to `/usr/share/pixmaps`

scu-qt.protocol (KDE)

