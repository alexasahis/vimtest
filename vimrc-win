"Vim Bundle Manager
set nocompatible
filetype off
set rtp+=~/.vim/bundle/vundle/
call vundle#rc()
Bundle 'gmarik/vundle'
Bundle 'scrooloose/nerdtree'
Bundle 'tpope/vim-rails'
Bundle 'tpope/vim-bundler'
Bundle 'vim-scripts/TailMinusF'
Bundle 'vim-scripts/dbext.vim'
filetype plugin indent on
" 
" Brief help
" :BundleList          - list configured bundles
" :BundleInstall(!)    - install(update) bundles
" :BundleSearch(!) foo - search(or refresh cache first) for foo
" :BundleClean(!)      - confirm(or auto-approve) removal of unused bundles
" 
" see :h vundle for more details or wiki for FAQ
" NOTE: comments after Bundle command are not allowed..

"
syntax on
set tabstop=2
set softtabstop=2
set shiftwidth=2
set noexpandtab
set ruler
set hlsearch
"columns	width of the display
set co=113
"lines	number of lines in the display
set lines=39
"window	number of lines to scroll for CTRL-F and CTRL-B
set window=38
 
"autocmd! bufwritepost .vimrc source %

"
" define OpenURL (OSX)
":command -bar -nargs=1 OpenURL :!open -a Safari 
":command -bar -nargs=1 OpenURL :!open 
":command -bar -nargs=1 OpenURL :!open <args> 
" define OpenURL (Windows)
:command -bar -nargs=1 OpenURL :!start cmd /cstart /b 
" define OpenURL (Linux)
":command -bar -nargs=1 OpenURL :!firefox 
":command -bar -nargs=1 OpenURL :!firefox <args>
" Keymaping
nmap \s :w 
nmap \q :q! 
nmap \f <c-f> " Maping '\f' to Ctrl-F (Page Down) for Mac
nmap \b <c-b> " Maping '\b' to Ctrl-B (Page Up) for Mac
nmap \d <c-d> " Maping '\d' to Ctrl-d (Half-Page Down) for Mac
nmap \u <c-u> " Maping '\u' to Ctrl-u (Half-Page Up) for Mac
nmap \r <c-r> " Maping '\r' to Ctrl-r (Redo) for Mac
nmap \w <c-w>w " Maping '\w' to Ctrl-w w (Window command) for Mac
