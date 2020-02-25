# Ariake Vim Color theme

Ariake dark is a post of the great Atom theme. It is not a direct port but is pretty close.

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

For neovim, add the following to your `.nvimrc`.


```viml
if (has("termguicolors"))
 set termguicolors
endif

" Theme
syntax enable
colorscheme ariake
```

## Vim

I have concetrated on the languages I write (JS,TS, Docker, JSON) but should be ok for others. If not drop my a line in the issues and let me know.
 
I will add more languages as I need them but happpy to accept PRs.

This theme leans of [vim-polyglot](https://github.com/sheerun/vim-polyglot) for the languages support

### JS
![js](https://github.com/jim-at-jibba/ariake-vim-colors/blob/master/assets/js.png)

### TS

![ts](https://github.com/jim-at-jibba/ariake-vim-colors/blob/master/assets/ts.png)

### Docker

![docker](https://github.com/jim-at-jibba/ariake-vim-colors/blob/master/assets/docker.png)

### JSON

![json](https://github.com/jim-at-jibba/ariake-vim-colors/blob/master/assets/json.png)

## Iterm2

I am also using zsh with oh-my-zsh and the [spaceship theme](https://github.com/denysdovhan/spaceship-zsh-theme)

![screenshot](https://github.com/jim-at-jibba/ariake-theme-iterm2/blob/master/screenshot.png)

## TODO:

- [x] Sort out folds
