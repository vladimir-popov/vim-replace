# vim-replace
Simple vim-plugin for replace selected text.

This is copy-pasted from the answer from the SO: https://stackoverflow.com/a/6171215/4190244

## How to install
Add to the `.vimrc`:
```
Plug 'vladimir-popov/vim-replace'
:PlugInstall
```

## How to use
In the visual mode press `Ctrl+r` to insert:
```
:%s/<selected text with esceped symbols>/<cursor will be here>/gc
```
to the command line.
