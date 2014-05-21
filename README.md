dotfiles
========

My personal dotfiles config inspired from: http://dotfiles.github.io

Why would I want my dotfiles on GitHub?

 - Backup, restore, and sync the prefs and settings for your toolbox. Your dotfiles might be the most important files on your machine.
 - Learn from the community. Discover new tools for your toolbox and new tricks for the ones you already use.
 - Share what you've learned with the rest of us.

Install
----

First install `rcm` and symlink file from this repo to your Home folder

```sh
brew install rcm
rcup -d /path/to/repo
```

If you have dotfiles which should stay in git

```sh
mkrc -d /path/to/repo file1 file2
```
