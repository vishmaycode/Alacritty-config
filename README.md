# Alacritty-config

### File
.config/alacritty.toml


### Shortcuts for tmux-sessionizer using alacritty
#### Super + Return = 

```shell
alacritty -e bash -ic "tmux-sessionizer; exec bash"
```
or
```shell
alacritty -e bash -c "tmux-sessionizer && exec bash"
```
or
```shell
alacritty -e bash -c "PATH=$PATH:/home/master/.fzf/bin tmux-sessionizer && exec bash"
```

#### Super + Ctrl + Return = 

```shell
alacritty
```

### References
[https://ostechnix.com/alacritty-terminal-emulator/](https://ostechnix.com/alacritty-terminal-emulator/)

[https://alacritty.org/config-alacritty.html](https://alacritty.org/config-alacritty.html)
