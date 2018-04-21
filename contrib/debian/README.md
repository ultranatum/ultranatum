
Debian
====================
This directory contains files used to package ultranatumd/ultranatum-qt
for Debian-based Linux systems. If you compile ultranatumd/ultranatum-qt yourself, there are some useful files here.

## ultranatum: URI support ##


ultranatum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ultranatum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ultranatum-qt binary to `/usr/bin`
and the `../../share/pixmaps/ultranatum128.png` to `/usr/share/pixmaps`

ultranatum-qt.protocol (KDE)

