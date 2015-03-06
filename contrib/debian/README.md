
Debian
====================
This directory contains files used to package fleacoind/fleacoin-qt
for Debian-based Linux systems. If you compile fleacoind/fleacoin-qt yourself, there are some useful files here.

## fleacoin: URI support ##


fleacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fleacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fleacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/fleacoin128.png` to `/usr/share/pixmaps`

fleacoin-qt.protocol (KDE)

