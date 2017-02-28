Installation:

    git clone git://github.com/drali/dotvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

Add the powerline fonts:

    cd ~/source/
    git clone https://github.com/powerline/fonts.git fonts
    cd fonts
    bash ./install.sh

Install fuzzfinder:

    git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
    ~/.fzf/install
