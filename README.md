Change in this fork: Space key expands abbrevtion even if the popup menu is visible. see `plugin/delimitMate.vim` line 265.

This plug-in provides automatic closing of quotes, parenthesis, brackets, etc., besides some other related features that
should make your time in insert mode a little bit easier, like syntax awareness (will not insert the closing delimiter
in comments and other configurable regions), <CR> and <Space> expansions (off by default), and some more.

Most of the features can be modified or disabled permanently, using global variables, or on a FileType basis, using
:autocmd.
