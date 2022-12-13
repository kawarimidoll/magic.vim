# magic.vim

Change the very-magic flag in search query.

## Usage

```vim
cnoremap <expr> <C-x> mi#magic#expr()
```

Works with:

- search
  - `/`
  - `?`
- commands
  - `:global`
  - `:lvimgrep`
  - `:lvimgrepadd`
  - `:sort`
  - `:substitute`
  - `:vglobal`
  - `:vimgrep`
  - `:vimgrepadd`

## inspired by

[monaqa/modesearch.vim](https://github.com/monaqa/modesearch.vim)
