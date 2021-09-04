# gh-shell
Save your favorite shell commands in a portable history file backed by a gist.

## Usage
```
$ gh shell list
$ gh shell add <command>
$ gh shell remove <command>
$ gh shell restore
```

Restoring the shell commands appends the list that is stored in the gist to your local shell history file (`$HISTFILE`). This allows you to save your favorite commands and then restore them on any machine, including as part of your dotfiles setup.
