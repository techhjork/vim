
[![Vim Logo](https://github.com/vim/vim/raw/master/runtime/vimlogo.gif)](https://www.vim.org)

![Vim](https://rawgit.com/darcyparker/1886716/raw/vimModeStateDiagram.svg)


Most of them below are in command mode

- `x`: to delete the unwanted character
- `A`: to undo the last the command and U to undo the whole line
- `CTRL-R`: to redo
- `:q!`: to trash all changes
- `dw`:  move the cursor to the beginning of the word to delete that word
- `2w`: to move the cursor two words forward.
- `3e`: to move the cursor to the end of the third word forward.
- `0`: (zero) to move to the start of the line.
- `d2w`:  which deletes 2 words .. number can be changed for deleting the number of consecutive words like d3w.
- `dd`:  to delete the line and 2dd to delete to line .number can be changed for deleting the number of consecutive words.


Folding is enabled for headers by default.

The following commands are useful to open and close folds:

- `zr`: reduces fold level throughout the buffer
- `zR`: opens all folds
- `zm`: increases fold level throughout the buffer
- `zM`: folds everything all the way
- `za`: open a fold your cursor is on
- `zA`: open a fold your cursor is on recursively
- `zc`: close a fold your cursor is on
- `zC`: close a fold your cursor is on recursively
