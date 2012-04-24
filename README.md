# Ftjerm v0.01 (fork of Stjerm)

## Improvements over the original version of Stjerm:
* __Improved__: completely rewritten Makefile.
* __Added__: setting custom border width (not only choosing one of the proposed styles). _(key -b)_
* __Added__: setting custom key for switching to the full-screen mode. _(key -fk)_
* __Added__: turning on/off text cursor blinking. _(key -cb)_
* __Added__: alternative cursor shape. _(key -cs)_

## Requirements
pkgconfig, gtk2, vte

## Installation
`sudo make install`

## Uninstallation
`sudo make uninstall`

## Running
Simply run: ftjerm

## Options
__key, -k__: Shortcut key which shows and hides ftjerm (eg: f12). If you don't specify a shortcut key, you  can only show/hide ftjerm if you run ftjerm with --toggle.
__fullscreenkey, -fk__: Shortcut key which toggle fullscreen mode of ftjerm (eg: f2). Default: F11.