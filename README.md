# tinygo.vim

This is a simple extension to add TinyGo support to Vim and Neovim.  Add
environment variables for tinygo and restart vim-lsp.  Using tinygo.vim, you
can easily integrate with gopls.

![](./tinygo-target-vim.gif)

## Installing

```
Plug 'sago35/tinygo.vim'
```

## Usage

If an argument is specified, vim-lsp will be restarted with that target
setting. If no argument is specified, it will open a list of targets.
In that case, target can be selected by pressing ENTER.

```
:TinygoTarget               open a list of targets.
:TinygoTarget [target]      vim-lsp will be restarted with that target setting
```
