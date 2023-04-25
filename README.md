To copy & paste after scrolling up in a tmux window:

`Cmd+R` (View->Hide/Allow mouse reporting)

alternatively:

`fn + option` -> `Cmd+C`

https://stackoverflow.com/questions/12287432/how-to-copy-to-system-clipboard-from-tmux-output-after-mouse-selection

Shortcuts to remember:

## Move pane to new window

`Ctrl-b` + `!`

## Move pane back to old window

`:join-pane -t:{previous}`

## Mouse copy-paste on ubuntu:

Hold `shift`

## Mouse copy-paste on mac:

Hold `fn`

## Set default command

E.g., to make bash your default shell for tmux on a remote server, add this to `.tmux.conf`:

```bash
set -g default-command /bin/bash
```

([source](https://unix.stackexchange.com/a/214086))


## new tmux (3.2) style

```
# https://gist.github.com/tbutts/6abf7fb5b948c066bf180922fb37adcf for tmux 3.2
set -g pane-border-style fg=white
set -g pane-active-border-style fg=cyan,bg=cyan
```
