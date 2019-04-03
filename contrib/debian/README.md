
Debian
====================
This directory contains files used to package profitbased/profitbase-qt
for Debian-based Linux systems. If you compile profitbased/profitbase-qt yourself, there are some useful files here.

## profitbase: URI support ##


profitbase-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install profitbase-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your profitbaseqt binary to `/usr/bin`
and the `../../share/pixmaps/profitbase128.png` to `/usr/share/pixmaps`

profitbase-qt.protocol (KDE)

