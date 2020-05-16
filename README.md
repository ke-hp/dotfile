# README #
Portable configs for vim/tmux/zsh.
## how to use it
### prepare dpendency
#### ubuntu
````sh
    sudo apt-get install git vcsh zsh python-pip tmux vim colordiff ctags
    sudo pip install powerline-status
    chsh -s $(which zsh)
````
#### OSX
````sh
    brew install git vcsh python mr tmux colordiff
    brew install --with-override-system-vim macvim
    pip install powerline-status
    for 10.5=> - SysPrefs, accounts, right-click (or control-click) on user, select advanced options, edit login shell field.
````
### clone this repo
````sh
    vcsh clone https://github.com/ke-hp/dotfile.git
````
### update
````sh
    mr update
````
