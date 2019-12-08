Basic bash status bar for dwm. This status bar requires the [status2d patch](https://dwm.suckless.org/patches/status2d/) for the colors to work. My [personal build of dwm](https://github.com/aaronkirkman/dwm) includes the patch.


To use it, place code like this in your `xinitrc`:

	#!/usr/bin/env bash
	while true; do
		statusbar
		sleep 60;
	done &
	exec path/to/dwm
