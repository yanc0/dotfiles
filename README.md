# dotfiles
My configs

## gnome-console

dconf dump /org/gnome/terminal/ | $(pwd)/gnome-terminal.dconf
cat $(pwd)/gnome-terminal.dconf | dconf load /org/gnome/terminal/

## vim 

ln -sf $(pwd)/.vimrc ~/

## tmux

ln -sf $(pwd)/.tmux ~/

## bash

ln -sf $(pwd)/.bachrc ~/
