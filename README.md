# vimrc

Minimal vimrc

set nu
set tabstop=4
set shiftwidth=4

autocmd Filetype c,cpp,h,hpp,cxx,hxx,cuda setlocal expandtab

set autochdir
set autoindent
set smartindent
set cindent
set list listchars=trail:·,nbsp:·,tab:»\ ,eol:⌋
set list

autocmd InsertEnter,InsertLeave * set cul!

nnoremap <C-J> <C-W><C-J>
nnoremap <C-K> <C-W><C-K>
nnoremap <C-L> <C-W><C-L>
nnoremap <C-H> <C-W><C-H>
