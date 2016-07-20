# Vim Armenian Keymaps

This is a set of Vim keymaps for the Armenian alphabet. The keymaps can be used
to type Armenian characters in Insert mode while retaining standard
functionality in Normal mode.

Most of these mappings are based on the xkeyboard-config Armenian keymaps.
`armenian-western-alt-utf-8.vim` is an experimental hybrid of the Western
Armenian and phonetic keymaps that is subject to change.

Please feel free to submit additional keymaps or corrections.

## Setup

Copy or link a keymap file to the directory `/usr/share/vim/vim74/keymap/`,
then enable the keymap in your `.vimrc` using the `keymap` option.

For example, to use the Western Armenian keymap, copy or link
`armenian-western_utf-8.vim` to the directory `/usr/share/vim/vim74/keymap/`,
then enable the keymap in your `.vimrc`:

```vim
set keymap=armenian-western_utf-8
```

You can switch between Armenian and Latin characters in Insert mode using
<kbd>Ctrl-^</kbd>. To disable the keymap at Vim startup, add the following
lines to your `.vimrc`:

```vim
set iminsert=0
set imsearch=0
```

For more information on keymaps, see `:help mbyte-keymap`.
