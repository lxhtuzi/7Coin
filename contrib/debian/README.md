
Debian
====================
This directory contains files used to package 7Coind/7Coin-qt
for Debian-based Linux systems. If you compile 7Coind/7Coin-qt yourself, there are some useful files here.

## 7Coin: URI support ##


7Coin-qt.desktop  (Gnome / Open Desktop)
To install:

        sudo desktop-file-install 7Coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your 7Coin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

7Coin-qt.protocol (KDE)

