Simple personal VIM config for programming
==========================================

General features:
 * disabled `<esc>`, use `jk`, `<c-c>` or `<c-[>` instead
 * python `syntax folding` - folds functions and classes
 * manage plugins by `vim-plug` https://github.com/junegunn/vim-plug
 * plugins are put at `~/.cache/vim`

Python features:
 * autocomplete by jedi (`pip install jedi`)
 * check `PEP8` on write (`pip install flake8`)

Navigation mappings:
 * `,/` - split current buffer verticaly

 * `,l` - list buffers
 * `,,` - goto previous buffer
 * `,.` - goto next buffer
 * `,1-0` - goto specific buffer (1-10)

Code mappings:
 * `tt` - toggle tagbar and focus it if opened
 * `to` - open tagbar and close after selecting tag

Operators mapping like `d`, `c`, `r`:
 * `<operator>p` - operate inside `()`, f.i.: `dp` - delete content between `()`
 * `<operator>q` - operate inside `''`, f.i.: `dp` - delete content between `''`
 * `<operator>Q` - operate inside `""`, f.i.: `dp` - delete content between `""`
 * `<operator>ar` - find next `(` and operate between `()`, f.i.: `car`

`vimrc` mappings:
 * `,re` - edit `$MYVIMRC`
 * `,rs` - source `$MYVIMRC`

Plugins:
 * https://github.com/chriskempson/base16-shell
 * https://github.com/davidhalter/jedi-vim
 * https://github.com/dietsche/vim-lastplace
 * https://github.com/editorconfig/editorconfig-vim
 * https://github.com/ervandew/supertab
 * https://github.com/honza/vim-snippets
 * https://github.com/hynek/vim-python-pep8-indent
 * https://github.com/kshenoy/vim-signature
 * https://github.com/majutsushi/tagbar
 * https://github.com/nathanaelkane/vim-indent-guides
 * https://github.com/rafi/vim-tinyline
 * https://github.com/SirVer/ultisnips
 * https://github.com/vim-syntastic/syntastic

Theme:
 * https://github.com/morhetz/gruvbox

Screenshot
----------
![vim screenshot](https://raw.githubusercontent.com/onjin/.vim/master/screenshot.png)
