# dotfiles

vim 8.1 or later is required. To install the latest version of vim, enter the following command.
```
$ sudo add-apt-repository ppa:jonathonf/vim
$ sudo apt update
$ sudo apt install vim
```

## Install Requirements
```
$ sudo apt update
$ sudo apt install vim-gtk3 curl python3-pip xsel
$ pip3 install neovim
```

## Install dein and fonts
```
$ cd ~/dotfiles/vim
$ ./setup_dein.sh
$ ./install_font.sh
```

## Edit vimrc and tmux.conf
```
$ echo "source ~/dotfiles/vim/vimrc" > ~/.vimrc
$ echo "source ~/dotfiles/tmux/tmux.conf" > ~/.tmux.conf
```
