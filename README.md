# Config files 

## Redshift

$ ln -s ~/code/dotfiles/config-dotfiles/redshift.conf ~/.config/redshift.conf

## Git
$ ln -s ~/code/dotfiles/config-dotfiles/.gitconfig ~/.gitconfig

## Flake8

$ ln -s ~/code/dotfiles/config-dotfiles/flake8 ~/.config/flake8

## Ipython

- Create profile:
$ ipython profile create

- Link file:
$ ln -s ~/code/dotfiles/config-dotfiles/ipython_config.py ~/.ipython/profile_default/ipython_config.py

# Themes

## Gnome shell theme

Change pink color by applying following patch

From `~/.themes/Ant-Dracula`:
$ git apply /path/to/dotfiles/Ant-Dracula.patch

## Emacs dracula theme

From `~/.emacs.d/.cask/25.2/elpa/dracula-theme-.../`:
$ patch < /path/to/dotfiles/dracula-theme.el.patch


