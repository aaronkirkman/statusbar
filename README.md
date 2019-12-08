Basic bash status bar for dwm. Used in `xinitrc` like this:

	#!/usr/bin/env bash
	while true; do
		statusbar
		sleep 60;
	done &
	exec path/to/dwm
