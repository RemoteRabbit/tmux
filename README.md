# Tmux config

This repo is home to my config setup for tmux. It is always changing and almost always working.

## How to use

### My way

```shell
mkdir -p $HOME/repos/personal
git clone https://github.com/remoterabbit/tmux $HOME/repos/personal
ln -sf $HOME/repos/personal/tmux $HOME/.config
```

### Classic

```shell
git clone https://github.com/remoterabbit/tmux
```

### Classic with placement

```shell
git clone https://github.com/remoterabbit/tmux $HOME/.config/
```

### No Git Please

```shell
git clone https://github.com/remoterabbit/tmux $HOME/.config
rm -rf $HOME/.config/tmux/.git
```

## Keymaps

| Key | What it do |
| --- | ---------- |
| Ctrl + a | prefix |
| Prefix + alt + u | TPM auto uninstall |
| Prefix + I | TPM install |
| Prefix + F | Tmux Filter/grep |
| Prefix + z | Zoom in/out of pane |
| Prefix + s | Session wizard with zoxide |

## Plugins (TPM)

I use [TPM](https://github.com/tmux-plugins/tpm) (Tmux Package Manager) to handle all my package install and update needs.

### How to get started

Once you have the repo pulled and setup you'll need to install the plugins. This can be done by `<prefix>I` as a reminder the `prefix` is changed in
this setup to `<CTRL>a`.
This should bring up a screen in tmux and show that it's installing the plugins.

### What each plugin is for

| Name | Description |
| ---- | ----------- |
| [27medkamal/tmux-session-wizard](https://github.com/27medkamal/tmux-session-wizard) | Works with zoxide and fzf to replace the session manager to
more easily create and manage sessions |
| [b0o/tmux-autoreload](https://github.com/b0o/tmux-autoreload) | Used to automatically reload `tmux.conf` upon change |
| [catppuccin/tmux](https://github.com/catppuccin/tmux) | My favorite colorscheme, with this I use the mocha flavor |
| [christoomey/vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator) | Adds in vim movement commands to move around tmux
sessions/windows/tabs/panes |
| [jaclu/tmux-power-zoom](https://github.com/jaclu/tmux-power-zoom) | Similar to ZenMode from nvim, allows you to toggle zoom into an individual
pane |
| [MaximilianGaedig/tmux-filter](https://github.com/MaximilianGaedig/tmux-filter) | A Grep style search for tmux |
| [tmux-plugins/tmux-continuum](https://github.com/tmux-plugins/tmux-continuum) | Works in tandum with resurrevt to add in autosaves to keep plugins
list |
| [tmux-plugins/tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect) | Allow you to return to a tmux session even after computer restart |
| [tmux-plugins/tpm](https://github.com/tmux-plugins/tpm) | Plugin manager of Tmux |

## Notes
