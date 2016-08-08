g
=
A collection of Zsh functions to augment Git.

![g](https://raw.github.com/eriknomitch/g/master/misc/g.png)

Requirements
------------
* Zsh
* Git

Installation
------------
Clone the repository to `~/.g` and add `source $HOME/.g/g.zsh` to your `~/.zshrc`.

Here's a one-liner:

```Bash
$ git clone git@github.com:Prelang/g.git ~/.g && echo "source \$HOME/.g/g.zsh" >> ~/.zshrc
```

Then, quit and restart your terminal instances.

Commands
--------

###Status###

**g**

Without arguments, *g* will display a custom, colored, and formatted git status including:
* Repository status (clean or unclean)
* Current branch and number of branches
* List of untracked files
* Short diff

Any arguments to *g* will first try to match a shortcut.  If a *g* shortcut is not matched, arguments to *g* will fall back to git allowing usage of *g* as a normal alias to `git`.

###Quick Commands###

**g cm \<commit-message\>**

*Commit all with message*

**g cmp \<commit-message\>**

*Commit all with message and push*

###Prompts###

**g au**

Prompts to add all untracked files in the current repository

**g ru**

Prompts to remove all untracked files in the current directory

###Aliases###

**g l**

`git log`

**g b**

`git branch`

**g d**

`git diff`

**g s**

`git status`

**g ls**

`git ls-files`

**g lsd**

`git ls-files --deleted`

**g lso**

*List untracked files excluding ignored files*

`git ls-files --other --exclude-standard`

**g ps**

`git push`

**g psa**

`git push all`

**g pl**

`git pull`

Credits
-------
Erik Nomitch: erik@nomitch.com
