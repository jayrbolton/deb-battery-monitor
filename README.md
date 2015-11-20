A simple low-level battery monitor daemon for your minimal Debian or Ubuntu build (I use xmonad with no toolbar).

Will monitor your battery minutes left, sending a notification as the battery runs low (with some quotes from Hackers) and will hibernate at 5m

Requires: `pm-utils acpi bc notify-osd`

#### installation
- Place daemon/battery-monitor into your /etc/init.d
- Place bin/battery-monitor into your /usr/sbin

