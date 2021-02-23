# VIM

## Requirements
- Golang
- Vim-Plug
- Python 3.5+

## Checkout

```sh
git clone https://github.com/lgaetecl/vim-config.git ~/.vim
```

## Config .vimrc o init.vim  

```sh
call plug#begin('~/.vim/plugged')
call plug#end()

source ~/.vim/config.vim
source ~/.vim/plugins.vim
source ~/.vim/plugins-config.vim
```
## Install

```sh
vim +PlugInstall
```
