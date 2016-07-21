# Vim Armenian Keymaps

This is a set of Vim keymaps for the Armenian alphabet. The keymaps can be used
to type Armenian characters in Insert mode while retaining standard
functionality in Normal mode.

The `master` branch provides a pair of common mappings for the Western and
Eastern dialects that cover the full alphabet and all standard punctuation
marks. The `alt` branch provides an alternate set of mappings based on the
xkeyboard-config Armenian keymaps.

Please feel free to submit additional keymaps or corrections as pull requests
or patches sent to <vim@benlinskey.com>.

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

## Layouts

### Eastern Armenian

![Eastern Armenian keyboard layout](img/KB_Eastern_Armenian.svg.png)

*The original uploader was Pokajanje at English Wikipedia. (Transferred from
en.wikipedia to Commons.) [[CC BY-SA 3.0][]],
[via Wikimedia Commons](https://commons.wikimedia.org/wiki/File%3AKB_Eastern_Armenian.svg).*

### Western Armenian

![Western Armenian keyboard layout](img/KB_Western_Armenian.svg.png)

*The original uploader was Pokajanje at English Wikipedia. (Transferred from
en.wikipedia to Commons.) [[CC BY-SA 3.0][]],
[via Wikimedia Commons](https://commons.wikimedia.org/wiki/File%3AKB_Western_Armenian.svg).*

[CC BY-SA 3.0]: http://creativecommons.org/licenses/by-sa/3.0
