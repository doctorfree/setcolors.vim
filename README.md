setcolors.vim
=============

Install via [Pathogen](https://github.com/tpope/vim-pathogen):

    cd ~/.vim/bundle
    git clone https://github.com/doctorfree/setcolors.vim.git setcolors

Install via [vim-plug](https://github.com/junegunn/vim-plug):

    Plug 'doctorfree/setcolors.vim'

Default list of colorschemes through which to cycle:

    ['asciiville', 'everforest', 'cool', 'desertink', 'distinguished', 'hybrid', 'luna', 'molokai', 'solarized', 'zenburn']

Override list of colorschemes through which to cycle, for example:

    let g:mycolorschemes = ['asciiville', 'everforest', 'cool', 'desertink']

Sets the Airline theme to the same colorscheme

Cycle through colorschemes and airline themes using the default key bindings:

    <F7> Previous colorscheme and airline theme
    <F8> Next colorscheme and airline theme
    <F9> Random colorscheme and airline theme
