# magic.vim

Change the very-magic flag in search query.

![demo](https://user-images.githubusercontent.com/8146876/207235817-8efa328e-d319-4a01-9b68-33e2f3f19407.gif)

## Usage

```vim
cnoremap <expr> <C-x> magic#expr()
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
