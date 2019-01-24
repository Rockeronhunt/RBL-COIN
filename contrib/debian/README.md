
Debian
====================
This directory contains files used to package royalbritishlegiond/royalbritishlegion-qt
for Debian-based Linux systems. If you compile royalbritishlegiond/royalbritishlegion-qt yourself, there are some useful files here.

## royalbritishlegion: URI support ##


royalbritishlegion-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install royalbritishlegion-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your royalbritishlegion-qt binary to `/usr/bin`
and the `../../share/pixmaps/royalbritishlegion128.png` to `/usr/share/pixmaps`

royalbritishlegion-qt.protocol (KDE)

