# wolfram-vim
Wolfram Language syntax coloring file for VIM

Installation:

```
git clone git@github.com:arnoudbuzing/wolfram-vim.git
```

and then copy `wl.vim` under `~/.vim/syntax/`

Enable in VIM

```
set syntax=wl
```

Enable automatically when VIM is started, add the following to `~/.vimrc`:

```
autocmd BufNewFile,BufRead *.wl set syntax=wl
autocmd BufNewFile,BufRead *.m set syntax=wl
```
