dotfiles
========

My DotFiles

/vim contents
================

includes
- pathogen
- zenburn
- syntastic

/git contents
================

gitignore for
- tox
- python
- etc...

Installation
============

```
cd ~
git clone https://github.com/neogenix/dotfiles.git neogenix-dotfiles
cd ~/neogenix-dotfiles
git submodule init
git submodule sync
cd ~
ln -sf neogenix-dotfiles/vim/.vim ~/.vim
ln -sf neogenix-dotfiles/vim/.vimrc ~/.vimrc
ln -sf neogenix-dotfiles/git/.gitignore ~/.gitignore
```
