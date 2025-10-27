# Vim Armenian Keymaps

This is a set of Vim keymaps for the Armenian alphabet. The keymaps can be used
to type Armenian characters in Insert mode while retaining standard
functionality in Normal mode. For more information on Vim keymaps, see
`:help mbyte-keymap`.

`armenian-eastern_utf-8.vim` and `armenian-western_utf-8.vim` are included in
the [Vim source code][]. The `extra` directory contains additional alternate
keymaps.

Diagrams of the [Eastern][eastern-img] and [Western][western-img] layouts are
available on Wikimedia.

## Requirements and Installation

Your Vim installation must be compiled with the `+keymap` feature. Use
`:version` to check which features are available.

Your version of Vim may come with the primary keymaps preinstalled. If they are
not installed or you'd like to use one of the `extra` keymaps, copy or link
your desired keymap(s) to `~/.vim/keymap/` or another location in Vim's runtime
path (see `:h runtimepath`).

To use a keymap, you’ll need to enable it in your `.vimrc` using the `keymap`
option. For example, to use the Western Armenian keymap, ensure that
`armenian-western_utf-8.vim` is in your Vim runtime path, then enable the
keymap in your `.vimrc`:

```vim
set keymap=armenian-western_utf-8
```

You can switch between Armenian and Latin characters in Insert mode using
<kbd>Ctrl-^</kbd> (i.e., <kbd>Ctrl-Shift-6</kbd> on a standard English keyboard
layout). To disable the keymap at Vim startup so that Insert mode
uses Latin characters by default, add the following lines to your `.vimrc`:

```vim
set iminsert=0
set imsearch=0
```

[Vim source code]: https://github.com/vim/vim
[eastern-img]: https://commons.wikimedia.org/wiki/File:KB_Eastern_Armenian.svg
[western-img]: https://commons.wikimedia.org/wiki/File:KB_Western_Armenian.svg
