## TMUX
MOUSE FREEEEEEEE
- split screens 
- perforce sync (session)
- create a persistent dashboard for monitoring servers?

### Config

- [~/.tmux.conf](https://github.com/pablo-meier/dotfiles/blob/master/.tmux.conf)

### Session commands
```
$ tmux
$ tmux new -s heyjin
$ tmux list-sessions
```

##### session attach
```
$ tmux attach
$ tmux a`
$ tmux attach -t heyjin
```

##### session detach
`Ctrl+t d`

### Window shortcuts
- `Ctrl+t c` open window
- `Ctrl+t x or &` close window
- `Ctrl+t ,` rename window 
- `Ctrl+t w` window list
- `Ctrl+t l n p (num)` move windows

### Pane shortcuts
- `Ctrl+t %` split horizontal
- `Ctrl+t “` split vertical
- `Ctrl+t <alt> arrows` zoom pane’s size
- `Ctrl+t space` change layout of pane
- `Ctrl+t o` move next pane
- `Ctrl+t {` move left pane
- `Ctrl+t }` move right pane
- `Ctrl+t arrows` move panes



