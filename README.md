<div align="center">

# zellij.fish 🐟

</div>

This is a [zellij](https://github.com/zellij-org/zellij) plugin for [fish](https://fishshell.com/). Inspired by or rather a port of [fish tmux plugin](https://github.com/budimanjojo/tmux.fish).

## Features

This plugin does the following:

- abbreviations for zellij

## Installation

First, make sure you have the recent version of tmux and fish as I don't test this on older version. Next, install this plugin with [Fisher](https://github.com/jorgebucaran/fisher):

```
fisher install MrHuxu/zellij.fish
```

## Abbreviations

| Abbreviation | Command                    | Description                                                                    |
| ------------ | -------------------------- | ------------------------------------------------------------------------------ |
| zac          | zellij action              | Send actions to a specific session                                             |
| zs           | zellij -s                  | Create a new named session                                                     |
| zsc          | zellij -l compact -s       | Create a new named session with compact layout(without tab bar and status bar) |
| zl           | zellij list-sessions       | Displays a list of sessions                                                    |
| za           | zellij attach              | Attach to a named session                                                      |
| zk           | zellij kill-session        | Kill a running named session                                                   |
| zka          | zellij kill-all-sessions   | Kill all running sessions                                                      |
| zd           | zellij delete-session      | Delete a named session                                                         |
| zda          | zellij delete-all-sessions | Delete all sessions                                                            |
| ze           | zellij edit                | Edit a file in a new pane                                                      |
| zef          | zellij edit --floating     | Edit a file in a floating pane                                                 |
| zr           | zellij run                 | Run a command in a new pane                                                    |
| zrf          | zellij run --floating      | Run a command in a floating pane                                               |

## License

MIT License
