
Debian
====================
This directory contains files used to package examinationd/examination-qt
for Debian-based Linux systems. If you compile examinationd/examination-qt yourself, there are some useful files here.

## examination: URI support ##


examination-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install examination-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your examination-qt binary to `/usr/bin`
and the `../../share/pixmaps/examination128.png` to `/usr/share/pixmaps`

examination-qt.protocol (KDE)

