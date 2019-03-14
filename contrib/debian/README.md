
Debian
====================
This directory contains files used to package legiond/legion-qt
for Debian-based Linux systems. If you compile legiond/legion-qt yourself, there are some useful files here.

## legion: URI support ##


legion-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install legion-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your legionqt binary to `/usr/bin`
and the `../../share/pixmaps/legion128.png` to `/usr/share/pixmaps`

legion-qt.protocol (KDE)

