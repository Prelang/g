g
=
g is a set of ZSH functions and scripts to automate and/or shorten common git tasks.

Requirements
------------
* Zsh
* Git

Installation
------------
Clone the repository to `~/.g` and add `source $HOME/.g/g.zsh` to your `~/.zshrc`.

Commands
--------
**g l**

Is a wrapper for `git log`

**g ls**

Is a wrapper for `git ls-files`

**g au** (**a**dd **u**ntracked files)

Is a prompt to add all untracked files in the current repository.

**g lso**

Is a wrapper for `git ls-files --other --exclude-standard`

Credits
-------
Erik Nomitch: erik@nomitch.com
