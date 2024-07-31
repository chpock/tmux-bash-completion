TMUX bash completion based on [bash-it's tmux completion](https://github.com/Bash-it/bash-it/blob/master/completion/available/tmux.completion.bash)

This is a fork of [imomaliev's tmux completion](https://github.com/imomaliev/tmux-bash-completion) with the following changes:
* fixed issue with `>` and `<` characters in session names

__Requires__ [bash-completion](https://github.com/scop/bash-completion) 1.2 or higher

Available completions
* commands
* files
* sessions
* windows

TODO
* use `list-sessions -F`
* check all cases for `complete -o default`
