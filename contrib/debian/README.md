
Debian
====================
This directory contains files used to package epayd/epay-qt
for Debian-based Linux systems. If you compile epayd/epay-qt yourself, there are some useful files here.

## epay: URI support ##


epay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install epay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your epay-qt binary to `/usr/bin`
and the `../../share/pixmaps/epay128.png` to `/usr/share/pixmaps`

epay-qt.protocol (KDE)

