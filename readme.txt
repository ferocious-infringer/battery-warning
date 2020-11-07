This is written in ZSH, not BASH.
Used to create custom warning depending on battery level, on Mac.

To install,
	- Copy battery-warning.plist to /Library/LaunchAgents
	- Copy battery-warning to /usr/local/bin
	- Run launchctl load /Library/LaunchAgents/battery-warning.plist

To customize warnings, edit /usr/local/bin/battery-warning file.
