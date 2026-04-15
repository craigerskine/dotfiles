# .dotfiles

My public dotfiles.

## Install
_Installs chezmoi and applies my dotfiles_

```sh
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply craigerskine
```

## Update
_Pulls my @latest dotfiles/settings from github_

```sh
chezmoi update
# or - if you have the cz alias set
cz update
```
