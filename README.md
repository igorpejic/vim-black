# black.vim

This is an easily installable adaptation of `black.vim` integration of [Black](https://github.com/psf/black).


## Install

Use your favorite plugin manager. 

[vim-plug](https://github.com/junegunn/vim-plug):

Plug 'igorpejic/vim-black'

[VundleVim](https://github.com/VundleVim/Vundle.vim)

Plugin 'igorpejic/vim-black'


## Settings

### Autosave

Add this to your `~/.vimrc`:
```vimrc

autocmd BufWritePost *.py execute ':Black'

```

## Thanks
This script was originally written by: Łukasz Langa.

The original version of the script can be found in the [black repository](https://github.com/psf/black/blob/master/plugin/black.vim).

