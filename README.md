# .dotfiles
My dotfiles

To use this repository effecitvely you have to link the files that you canfind here to the respecitve locations. The location should be the path you can find here as for example the oh-my-zsh/custom/themes/ path is the path for the files in the original oh-my-zsh directory (when installed).
You have to link the files using 'ln -s source(original file this repo) target(location where the application expect this file to be)'

Examples:
.gitconfig
ln -s ./.gitconfig ~/.gitconfig

aliases.zsh
ln -s ./oh-my-zsh/custom/ ~/.oh-my-zsh/custom/

