# Install Vim and plugins
* Install Vim package
  <pre>
  $ sudo apt-get install vim
  </pre>
* Install Vim's plugins manager
  <pre>
  $ mkdir -p ~/.vim/bundle
  $ cd ~/.vim/bundle
  $ git clone git://github.com/gmarik/vundle.git
  </pre>
* Install default vimrc
  <pre>
  $ vi ~/.vimrc
<pre>
" Install Vim Bundle Manager
set nocompatible			" for VIM
filetype off
set rtp+=~/.vim/bundle/vundle/
call vundle#rc()
Bundle 'gmarik/vundle'
Bundle 'scrooloose/nerdtree'
Bundle 'tpope/vim-rails'
Bundle 'tpope/vim-bundler'
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
syntax on				"
set tabstop=2
set softtabstop=2
set shiftwidth=2
set noexpandtab
set ruler				"
set hlsearch				"
"
" define OpenURL (OSX)
":command -bar -nargs=1 OpenURL :!open &ltargs&gt  
" define OpenURL (Windows)
":command -bar -nargs=1 OpenURL :!start cmd /cstart /b &ltargs&gt
" define OpenURL (Linux)
:command -bar -nargs=1 OpenURL :!firefox &ltargs&gt
" Keymaping
nmap \s :w&ltcr&gt 
nmap \q :q!&ltcr&gt 
nmap \f &ltC-f&lt " Maping '\f' to Ctrl-F (Page Down) for Mac
nmap \b &ltC-b&gt " Maping '\b' to Ctrl-B (Page Up) for Mac
nmap \d &ltC-d&gt " Maping '\d' to Ctrl-d (Half-Page Down) for Mac
nmap \u &ltC-u&gt " Maping '\u' to Ctrl-u (Half-Page Up) for Mac
nmap \r &ltC-r&gt " Maping '\r' to Ctrl-r (Redo) for Mac
nmap \w &ltC-w>w " Maping '\w' to Ctrl-w w (Window command) for Mac
</pre>
</pre>

* Install vim plugins and plugins help file
<pre>
$ vi
  <pre>
  :BundleInstall
  :h rails
  :h NERDTree
  :h bundler
  </pre>
</pre>
* Check plugins install
<pre>
$ vi
<pre>
  :Rails!
  :NERDTree
  :Bundle
</pre>
</pre>

