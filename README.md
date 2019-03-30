# Vim / Kakoune

> [Kakoune] integration for [Vim].

## Installation

Add to your `vimrc`:

``` vim
set runtimepath+=~/repositories/github.com/alexherbo2/kakoune.vim
```

## Usage

``` vim
nmap <CR> <Plug>(Kakoune)
vmap <CR> <Plug>(Kakoune)
```

- From Vim: Press <kbd>Return</kbd> to call Kakoune.
- From Kakoune: Press <kbd>Escape</kbd> to save and quit.

[Kakoune]: https://kakoune.org
[Vim]: https://vim.org
