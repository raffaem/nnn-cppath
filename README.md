# cppath

A nnn (=n³) plugin to copy (relative) file paths in the clipboard.

Works on both X11 and Wayland.

# Installation

1. Run `install.sh`.
2. Map to a keybinding with
```
NNN_PLUG='c:cppath;'
```

# Usage

1. Call a first time on file A.
2. Call a second time on file B.
3. If A!=B, the relative path from A to B is copied in the clipboard. If A==B, then the full path of A is copied in the clipboard.
