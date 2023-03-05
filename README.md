# tmux config
- tmux '>= 2.4' running inside Linux, Mac, OpenBSD, Cygwin or WSL
- awk, perl and sed
- outside of tmux, '$TERM' must be set to 'xterm-256color'
```
cd
git clone https://github.com/nevalions/tmux_config.git
cp -t ~/ tmux_config/.tmux.conf.local tmux_config/.tmux.conf
```
```
cd
git clone git@github.com:nevalions/tmux_config.git
ln -s -f tmux_config/.tmux.conf ~/.tmux.conf
cp tmux_config/.tmux.conf.local ~/.tmux.conf.local
```
Install tmux plugin manager
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
installed plugins for saving sessions tmux-continuum, Tmux Resurrect
```
Reload config in tmux prefix + r

```
    Здесь может быть
    Ваша реклама
```
