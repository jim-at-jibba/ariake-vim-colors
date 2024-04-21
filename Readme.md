# Ariake Vim Color theme

*N.B. I have now ported this theme to Neovim with a new lua version which can be found [here](https://github.com/jim-at-jibba/ariake.nvim/tree/main)*

Ariake dark and light is a post of the great Atom theme. It is not a direct port but is pretty close.

Included are iterm and alacritty themes

I have recently added Treesitter support. This is still WIP and will be improved over the coming weeks.
## Installation

All major plugin managers for vim/nvim are supported

 ```vim
<PACKAGE_MANAGER> 'jim-at-jibba/ariake-vim-colors'
 ```

For vim, add the following to your `.vimrc`.

 ```viml
" Theme
  syntax enable
" for vim 7
  set t_Co=256

" for vim 8
  if (has("termguicolors"))
   set termguicolors
  endif

colorscheme ariake
 ```

For neovim, add the following to your `.init.vim`.


```viml
if (has("termguicolors"))
 set termguicolors
endif

" Theme
syntax enable
set background=dark
" For the light theme
" set background=light
colorscheme ariake
```

## Vim

I have concentrated on the languages I write (JS,TS, Docker, JSON) but should be ok for others. If not drop my a line in the issues and let me know.

I will add more languages as I need them but happy to accept PRs.

This theme leans on [vim-polyglot](https://github.com/sheerun/vim-polyglot) for the languages support


### TS
![ts](https://github.com/jim-at-jibba/ariake-vim-colors/blob/master/assets/tsx.png)

### PHP
![php](https://github.com/jim-at-jibba/ariake-vim-colors/blob/master/assets/php.png)

## Iterm2

I am also using zsh with oh-my-zsh and the [spaceship theme](https://github.com/denysdovhan/spaceship-zsh-theme)

![screenshot](https://github.com/jim-at-jibba/ariake-theme-iterm2/blob/master/screenshot.png)

## TODO:

- [x] Sort out folds
