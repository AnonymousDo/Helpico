
Debian
====================
This directory contains files used to package helpicod/helpico-qt
for Debian-based Linux systems. If you compile helpicod/helpico-qt yourself, there are some useful files here.

## helpico: URI support ##


helpico-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install helpico-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your helpico-qt binary to `/usr/bin`
and the `../../share/pixmaps/helpico128.png` to `/usr/share/pixmaps`

helpico-qt.protocol (KDE)

