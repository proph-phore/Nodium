
Debian
====================
This directory contains files used to package Nodiumd/Nodium-qt
for Debian-based Linux systems. If you compile Nodiumd/Nodium-qt yourself, there are some useful files here.

## Nodium: URI support ##


Nodium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Nodium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Nodiumqt binary to `/usr/bin`
and the `../../share/pixmaps/Nodium128.png` to `/usr/share/pixmaps`

Nodium-qt.protocol (KDE)

