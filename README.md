# black.vim

This is an easy to install Vim plugin for  [Black](https://github.com/psf/black) code formatter.


## Install

Use your favorite plugin manager. 

[vim-plug](https://github.com/junegunn/vim-plug):

```vim
Plug 'igorpejic/vim-black'
```
 
or

[VundleVim](https://github.com/VundleVim/Vundle.vim):

```vim
Plugin 'igorpejic/vim-black'
```


## Settings

### Run on save

To run black on every save, add this to your `~/.vimrc`:

```vim
autocmd BufWritePost *.py execute ':Black'
```

## Thanks
This script was originally written by: Łukasz Langa.

The original version of the script can be found in the [black repository](https://github.com/psf/black/blob/master/plugin/black.vim).

