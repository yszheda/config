# config
My config files

## tmux

- Install [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

- Reload tmux environment so tpm is sourced:

```
# type this in terminal
$ tmux source ~/.tmux.conf
```

- Press `prefix + I` to install tmux plugins.

## zsh

- Install [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh):

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
or
```
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```
