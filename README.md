# dotfiles shared with chezmoi

Dotfiles manager | [Chezmoi](https://www.chezmoi.io)

> Initialize chezmoi repository

`chezmoi init`

> Add an existing dotfile

`chezmoi add ~/.bashrc`

> Edit source state of configuration file. 
> 
> This will open ~/.local/share/chezmoi/dot_bashrc in your $EDITOR.

`chezmoi edit ~/.bashrc`

> See what changes will be made

`chezmoi diff`

> Apply changes to actual dotfiles

`chezmoi -v apply`

> Restore dotfiles on another machine

```chezmoi init https://gitlab.com/username/dotfiles.gitchezmoi apply```

> Launch a shell in the source directory

`chezmoi cd`

> List the managed files in the destination directory

`chezmoi managed`

> Remove a target from the source state (stop managing)

`chezmoi forget ~/.bashrc`

> Pull latest changes from repository

`chezmoi update`