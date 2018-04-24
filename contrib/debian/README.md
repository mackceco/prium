
Debian
====================
This directory contains files used to package priumd/prium-qt
for Debian-based Linux systems. If you compile priumd/prium-qt yourself, there are some useful files here.

## prium: URI support ##


prium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install prium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your priumqt binary to `/usr/bin`
and the `../../share/pixmaps/prium128.png` to `/usr/share/pixmaps`

prium-qt.protocol (KDE)

