# dwmstackdeck
Two-window layout with one master and a deck of stack windows you can flip through.

TO-DO: add demo gif

## Usage
Press `Mod+S` to enable the layout, you'll see the `M|S` symbol on the bar. Flip windows as usual with `Mod+J` and `Mod+K`. If no windows in master stack, all windows will be fullscreen as in monocle mode. Only one master window is allowed(but i think i'll change that).

## Installation
Be careful so it won't mess up your current configuration.
```bash
cd <dwm-dir>
git am <path>/dwm-stackdeck-*.diff
make clean install
```
If the patch doesn't apply, install it by copying the snippets to dwm.c and config.def.h. Please report about failed patches.

## Future updates
I plan to add better controls and display opened windows on a panel(it could be the bar with tags, but there might be a problem in case it's occupied with status information)
