# vim-tab

A simple pathogen ready InsertTabWrapper I've used and am not sure where I
found.

Add the following to your vimrc once the plugin is installed:

    inoremap <tab> <c-r>=InsertTabWrapper()<cr>
    inoremap <s-tab> <c-n>imap<C-c><Esc>
