A simple low-level battery monitor daemon for your minimal Debian or Ubuntu build (I use xmonad with no toolbar).

Will monitor your battery minutes left, send a terminal notification at 30m left, and will hibernate at 10m

Requires: `pm-utils acpi espeak bc`

#### installation
- Place daemon/battery-monitor into your /etc/init.d
- Place bin/battery-monitor into your /usr/sbin

