# .dotfiles
My dotfiles

To use this repository effecitvely you have to link the files that you canfind here to the respecitve locations. The location should be the path you can find here as for example the oh-my-zsh/custom/themes/ path is the path for the files in the original oh-my-zsh directory (when installed).
You have to link the files using 'ln -s source (original file this repo) target (location where the application expects this file to be)

1. Clone repo into home directory (~)

`cd ~`

# Initialising ZSH with oh-my-zsh

2. Clone zsh repo (after intsalling zsh!) into its own .oh-my-zsh-Folder

`git clone git@github.com:ohmyzsh/ohmyzsh.git ~/.oh-my-zsh/` 

3. Remove placeholder files from official repository and replace them with the files of your repo


.zshrc

> `rm -rf ~/.zshrc`

> `ln -s ~/.dotfiles/oh-my-zsh/.zshrc.zsh ~/.zshrc`


aliases.zsh

> `rm -rf ~/.oh-my-zsh/custom/aliasas.zsh`

> `ln -s ~/.dotfiles/oh-my-zsh/custom/aliasas.zsh ~/.oh-my-zsh/custom/aliasas.zsh`


examples.plugins.zsh

> `rm -rf ~/.oh-my-zsh/custom/plugins/example/example.plugin.zsh`

> `ln -s ~/.dotfiles/oh-my-zsh/custom/plugins/example/example.plugin.zsh ~/.oh-my-zsh/custom/plugins/example/example.plugin.zsh`


examples.zsh-theme

> `rm -rf ~/.oh-my-zsh/custom/themes/example.zsh-theme`

> `ln -s ~/.dotfiles/oh-my-zsh/custom/themes/example.zsh-theme ~/.oh-my-zsh/custom/themes/example.zsh-theme`


# Initialising Git

Install git first!

.gitconfig:  
> `rm -rf ~/.gitconfig`

>`ln -s ~/.dotfiles/.gitconfig ~/.gitconfig`