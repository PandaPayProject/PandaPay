
Debian
====================
This directory contains files used to package pandapayd/pandapay-qt
for Debian-based Linux systems. If you compile pandapayd/pandapay-qt yourself, there are some useful files here.

## pandapay: URI support ##


pandapay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pandapay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pandapay-qt binary to `/usr/bin`
and the `../../share/pixmaps/pandapay128.png` to `/usr/share/pixmaps`

pandapay-qt.protocol (KDE)

