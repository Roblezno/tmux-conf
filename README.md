# Tmux config

Personal tmux configuration based on [Oh My Tmux][oh-my-tmux], with a
Kanagawa-inspired theme and the [tmux-menus][tmux-menus] plugin.

## Installation

```sh
git clone --recurse-submodules \
  https://github.com/Roblezno/tmux-conf.git \
  ~/.config/tmux
tmux
```

Oh My Tmux automatically installs TPM and the configured plugins under
`~/.config/tmux/plugins/` on first launch.

If the repository was cloned without its submodules, initialize them with:

```sh
git -C ~/.config/tmux submodule update --init --recursive
```

All personal customization belongs in `tmux.conf.local`. The `tmux.conf` file
is a symlink to the pinned Oh My Tmux configuration.

[oh-my-tmux]: https://github.com/gpakosz/.tmux
[tmux-menus]: https://github.com/jaclu/tmux-menus
