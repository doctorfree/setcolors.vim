# setcolors.vim

## Installation

Automatically installed during
[Asciiville](https://github.com/doctorfree/Asciiville)
initialization.

Install via [Pathogen](https://github.com/tpope/vim-pathogen):

    cd ~/.vim/bundle
    git clone https://github.com/doctorfree/setcolors.vim.git setcolors

Install via [vim-plug](https://github.com/junegunn/vim-plug):

    Plug 'doctorfree/setcolors.vim'

## Configuration

Default list of colorschemes through which to cycle:

    ['asciiville', 'everforest', 'cool', 'desertink', 'distinguished', 'hybrid', 'luna', 'molokai', 'solarized', 'zenburn']

Override list of colorschemes through which to cycle, for example:

    let g:mycolorschemes = ['asciiville', 'everforest', 'cool', 'desertink']

## Usage

This fork of the `setcolors.vim` plugin sets the Airline theme to the same
colorscheme as the selected Neovim colorscheme.

Cycle through colorschemes and corresponding airline themes using the default
key mappings:

    <F7> Previous colorscheme and airline theme
    <F8> Next colorscheme and airline theme
    <F9> Random colorscheme and airline theme

Set the list of color schemes used by the above (default is 'all'):

```vim
:SetColors all                     " all $VIMRUNTIME/colors/*.vim
:SetColors my                      " names built into script
:SetColors asciiville everforest   " these schemes
:SetColors                         " display current scheme names
```

Set the current color scheme based on time of day:

```vim
:SetColors now
```
