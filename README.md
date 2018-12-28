# Config files 

redshift.conf,~/.config/redshift.conf
.gitconfig,~/.gitconfig

# Themes

## Gnome shell theme

Change pink color by applying following patch

From `~/.themes/Ant-Dracula`:
$ git apply /path/to/dotfiles/Ant-Dracula.patch

## Emacs dracula theme

From `~/.emacs.d/.cask/25.2/elpa/dracula-theme-.../`:
$ patch < /path/to/dotfiles/dracula-theme.el.patch


