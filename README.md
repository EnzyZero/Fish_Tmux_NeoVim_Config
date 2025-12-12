# Tmux

Install tmux and the tmux packet manager tpm. Then create symlink:

```sh
# install tmux first!
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

# symlink tmux.conf into place
ln -s ~/.dotfiles/tmux/tmux.conf ~/.config/tmux/tmux.conf
```

# Fish

Symlink the dots:

```sh
ln -s ~/.dotfiles/fish/ ~/.config/
```

