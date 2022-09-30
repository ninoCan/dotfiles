# Dotfiles

My personal dotfiles conveniently stored in a repo. This should come together with a git alias and wrapper to make their management easier.

## Chezmoi

This are my dotfiles managed with [chezmoi](https://www.chezmoi.io/) for achieving -system inter-operability, and for integration with 3rd party secret stores.


### Archlinux

Freeze the installed packages (as in `pip freeze > requirements.txt`) with the command:

    $ pacman -Qqe > pkglist.txt
