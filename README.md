# cwm-statusbar

Minimal [cwm(1)](https://man.openbsd.org/cwm.1) statusbar to show:

- current active group
- group with windows open
- list of all groups
- datetime

## requirements

- [lemonbar](https://github.com/drscream/lemonbar-xft) - if you like to use xft version
- [siji](https://github.com/stark/siji) - if you like to use the glyphs
- bash

## usage

Get the latest version:

	git clone git@github.com:drscream/cwm-statusbar.git

Change the directory:

	cd cwm-statusbar

Start the reporting services:

	./xprop start
	./datetime start

Start the lemonbar:

	./statusbar start
