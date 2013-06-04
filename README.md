This is my ~/.vim dir:

Installation
============

Clone the repo:
`git clone https://github.com/yazug/vimfiles.git ~/.vim`

Grab the plugin submodules:
`cd ~/.vim && git submodule init && git submodule update`

Make sure vim finds the vimrc file by either symlinking it:
`ln -s ~/.vim/vimrc ~/.vimrc`

or by sourcing it from  your own ~/.vimrc:
`source ~/.vim/vimrc`


Notes:
========
Based on https://github.com/scrooloose/vimfiles.git

Update Submodules
=================
git submodule foreach git pull origin master
