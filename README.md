# Dotfiles

My personal dotfiles conveniently stored in a repo. This should come together with a git alias and wrapper to make their management easier. 

## From scratch

If you need to start this kind of repo all over again then, these are the step to reproduce.

Create the repo

    $ git init --bare $HOME/.dotfiles.git

Add alias to your rc file. Something like:

    $ alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles.git/ --work-tree=$HOME'

Add the 'sanity configurations' (do not show untracked files):

    $ dfl config --local status.showUntrackedFiles no

Customized .gitignore file name to your choice: eg.

    $ dfl config --local core.excludesFile=.dflignore

