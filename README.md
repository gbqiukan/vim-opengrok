vim-opengrok: opengrok interface for vim
========================================

Inspired by [youngker/eopengrok.el](https://github.com/youngker/eopengrok.el)

![vim-opengrok screenshot](https://raw.github.com/asenac/vim-opengrok/master/og-mode.gif)

Installation
------------

    Plugin 'asenac/vim-opengrok'

Configuration
-------------

    let g:opengrok_jar = '/path/to/opengrok/lib/opengrok.jar'

Commands
--------

    :OgIndex /path/to/index

Creates an index for the directory specified.

    :OgReIndex

Updates the index that contains the current directory.

    :OgSearch [f|d|r|p]

Searches in the index and displays the results in Vim's location list.

    :OgSearchCWord

Searches word under the cursor and displays the results in Vim's location list.

    :OgMode

Interactive queries displaying the results in a special buffer (see screenhost
above).
