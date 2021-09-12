```
set enc=utf-8
set fenc=utf-8
set termencoding=utf-8

" use indentation of previous line
set autoindent
" use intelligent indentation for C
set smartindent

set tabstop=4        " tab width is 4 spaces
set shiftwidth=4     " indent also with 4 spaces
set expandtab

set textwidth=120
syntax on

colorscheme peachpuff

set number relativenumber

set showmatch       " highlights matching parenthesis, e.g. (  )

set hlsearch
set incsearch

set wrap
set linebreak       " dont wrap lines in the middle of word

set scrolloff=5     " scroll to ensure 5 lines around cursor line
set sidescrolloff=5 " same, but characters
" Interface
set wildmenu        " menu for tab-completion
set title           " filename in title
set noerrorbells    " dont beep on errors
set ruler           " show position in bar
set showcmd         " show operator-pending minicommands
set cursorcolumn    " Slightly darker column at cursor
highlight CursorColumn ctermbg=16
"235 is brigter

set history=1000
set nrformats-=octal "no octal numbers
```
