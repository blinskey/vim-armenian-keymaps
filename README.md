# Vim Western Armenian Keymap

This is a Vim keymap for the Armenian alphabet. It can be used to type Armenian
characters in Insert mode while retaining standard functionality in Normal
mode.

This keymap is based on a standard Western Armenian keyboard layout, but it can
also be used to write Eastern Armenian.

## Setup

Copy or link `western-armenian_utf-8.vim` to the directory
`/usr/share/vim/vim74/keymap/`, then enable the keymap in your `.vimrc`:

```vim
set keymap=western-armenian_utf-8
```

You can switch between Armenian and Latin characters in Insert mode using
<kbd>Ctrl-^</kbd>. To disable the keymap at Vim startup, add the following
lines to your `.vimrc`:

```vim
set iminsert=0
set imsearch=0
```

For more information on keymaps, see `:help mbyte-keymap`.
