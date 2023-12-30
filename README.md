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

## Plugins (TPM)

I use [TPM](https://github.com/tmux-plugins/tpm) (Tmux Package Manager) to handle all my package install and update needs.

### How to get started

### What each plugin is for

## Notes

- [ ] Finish the docs
