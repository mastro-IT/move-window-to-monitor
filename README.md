# move-window-to-monitor
This simple script for X11/Xorg moves the active window to another display.

The selected display will be measured for resolution and position on the desktop.
The active window will be shown center on the selected display.
If the active window was maximized it will be maximized on destination.

You can run `xrandr --listmonitors` to determine the correct display-number, don't forget to add 1!

### Dependencies
- X11/Xorg
- wmctrl
- xdotool
- x11-xserver-utils

### Installation
1. Copy to /usr/bin/move-window-to-monitor
2. chmod +x /usr/bin/move-window-to-monitor
3. Add Keyboard-Shortuts to your Desktop-Environment

### Usage
```
move-window-to-monitor <number>

<number> is the number of the wanted display.
1 = Main display
2,3,4,5 = other displays
```

### Author
Marcus Orthbandt (https://www.mastro-it.de)