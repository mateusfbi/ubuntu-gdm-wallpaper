# GDM Login screen background changer
Script for GNOME 3.36+ with GNOME Shell themes packed inside /usr/share/gnome-shell/gdm3-theme.gresource.

This script allows change background on login screen.

# Tested on:
Ubuntu 20.04

But should work on any distro with /usr/share/gnome-shell/gdm3-theme.gresource file.

```shell
Script requires gresource binary (glib2 or glib2-devel library):
# Ubuntu: 
sudo apt install libglib2.0-dev-bin
```
# Usage 
```shell
set-gdm-wallpaper.sh /path/to/image.png
# (use --resize N option for fixing multiple monitor issues)
```
# Recovering 
If GDM load failed, then press ALT+F6 and:
```shell
set-gdm-wallpaper.sh --uninstall
OR
cp /usr/share/gnome-shell/gdm3-theme.gresource.backup /usr/share/gnome-shell/gdm3-theme.gresource
```

# Credit and Licences
wallpaper-gnome.png: https://www.opendesktop.org/s/Gnome/p/1071929/
