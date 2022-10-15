
Debian
====================
This directory contains files used to package kafeniocoind/kafeniocoin-qt
for Debian-based Linux systems. If you compile kafeniocoind/kafeniocoin-qt yourself, there are some useful files here.

## pivx: URI support ##


kafeniocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kafeniocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kafeniocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/kafeniocoin128.png` to `/usr/share/pixmaps`

kafeniocoin-qt.protocol (KDE)

