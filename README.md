# cariboublocker for Gnome Shell 3.36

Available at: https://extensions.gnome.org/extension/3222/block-caribou-36/

Based on https://github.com/keringar/cariboublocker.

Change some naming to be compatible with Gnome Shell 3.36.

There are some naming changes in Gnome Shell, so the original project no longer works on some Gnome Shell versions (For me, it works on Fedora 31 with gnome-shell-3.34.5 and Xorg, but not on Fedora 32 with gnome-shell-3.36.3 and Xorg). 

## Test Log
* 13 Jun 2020: Fedora 32 with gnome-shell-3.36.3 and Xorg
* 20 Feb 2021: Fedora 33 with gnome-shell-3.38.4 and Xorg

## Change Log

* Replace `Keyboard` with `KeyboardManager` in `extensions.js`.

## Relevant Code

* https://gitlab.gnome.org/GNOME/gnome-shell/-/blob/master/js/ui/keyboard.js

## Development Hints

[Looking Glass](https://wiki.gnome.org/Projects/GnomeShell/LookingGlass) is very helpful for debugging (saves my time installing an IDE etc).

To create a zip file for https://extensions.gnome.org/upload/, use `zip -j a.zip extension.js metadata.json`

# Original README.md from https://github.com/keringar/cariboublocker

RESOLVED https://bugs.launchpad.net/ubuntu/+source/gnome-shell/+bug/1723857

## cariboublocker
Prevents caribou from appearing when you use a touchscreen with the on screen keyboard disabled

## Installation
1. https://extensions.gnome.org/extension/1326/block-caribou/
2. You may need to install an extension, Gnome Shell Integration, see the gnome extensions [about](https://extensions.gnome.org) page for more details.
3. Click the toggle flag in the top right to ON.
